# linux-noc-monitor
Command line monitoring tool which reads a list of target hosts/domains from a config file, checks ICMP latency, packet loss, and DNS resolution. It will also log timestamped results to a file and trigger an alert if an endpoint fails three consecutive checks.
