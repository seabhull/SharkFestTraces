# SharkFestTraces
Trace Files for SharkFest 2020 - Troubleshooting Cloud Network Outages


Analyze Trace File (3 files provided) 
1) Open File
2) Display Filter - tcp.analysis.flags==1
3) IO Graph
    - Throughput (Packets/sec)
    - tcp.analysis.flags==1 - Throughput (pps)
    - tcp.analysis.retransmission==1 - throughput (pps)
4) Find First Retransmitted or Dup ACK Packet
    - Find last working bidirectional traffic
    - Identify direction of loss (AWS 10.0.2.x)
5) Identify Time Length of Impact
