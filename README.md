# docker-swarm
TCP 2377 - cluster management & raft sync communications
TCP, UDP 7946 - control - pane gossip discovery communication between all nodes
UDP 4789 - data pane - VXLAN overlay network traffic
Custom 50 - overlay network with the encryption option
