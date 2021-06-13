# pcap-analysis-automation

## main.py
> **extract session packets as pcap**
1. retrieve list of packet timestamps in the session
2. extract pcap file from .tar.gz
3. write a new pcap file containing session packets only

## snort.py/suricata.py
> **run snort/suricata for all pcap files under given directory**

snort : `python snort.py [pcap_dir] [log_dir]`

suricata : `python suricata.py [pcap_dir] [log_dir]`

## metadata_generator.py
> **generates a report of given session info**

With given date, isp, id and timestamp, the report generated by the generator contains the metadata such as start/end time, total packet number, IP source, etc.
