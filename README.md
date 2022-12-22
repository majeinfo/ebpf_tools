The `orphan_syn` script is a Python script that listens to retransmission of `SYN_SENT` TCP packets.
When no answer is received, it displays the IP address and the Port of the server the host is trying to reach.
This script has proven its usefulness when my own Web servers started to hang for 30s because they could not reach remote API servers.
