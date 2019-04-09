# Distributed-Password-Cracker

A simple password cracker that uses Multi-threading to connect to multiple clients. Clients then brute-force on an MD5 hashed password until it finds a match (which is guaranteed in most cases). 

The user inputs the MD5 hashed password that he wishes to crack, the server then receives it and sends it over with every thread created.

The Cracker can currently crack passwords that only contain lower case english letters and/or numbers.
