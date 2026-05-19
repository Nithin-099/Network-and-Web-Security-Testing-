# Network Analysis

Wireshark was used to capture and analyze HTTP traffic transmitted between the client and server.

HTTP POST requests were filtered using:

http.request.method == "POST"

The captured packets showed plaintext communication containing login credentials.

This demonstrates the risks of transmitting sensitive information over unencrypted HTTP connections.