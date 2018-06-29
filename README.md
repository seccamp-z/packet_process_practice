# Packet Processing

Some lesson about packet processing using c-lang.

## Practice: extraction image data from the traffic

- ``icmpdata.pcap`` is a pcap-datafile of some icmp-traffic. (ping-pong traffic)
- In general, Ping's packet includes some extra data (ex. ``#$%&'()*+,-./01234567``)
- In this case, ``icmpdata.pcap`` includes the fragmented image-data.
- Please extract the image data from the traffic.
- You can get the image-data, when you defragment each fragmented datas.
- You may get the image-data same as ``icmpdata.jpg``.
- You must program using only C/C++
- You must not use the extra lib to analyze packet.
- But you can use the some extra lib to reaad packet from the pcapfile.


