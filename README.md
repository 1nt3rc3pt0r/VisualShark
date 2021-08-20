# VisualShark
A visual-analysis tool that geolocates source/destination IPs obtained from pcap files.  Useful for visualizing connections

# Directions
- Replace the SourceIP with either 'srcip' or a fixed external IP address in geoip-map.py (Line is commented)
- Pipe output to KML file
  - $ python3 ./geoip-map.py > data.kml
- Upload to MyMaps on Google to visualize data
