# kahuna-tally
Grass Valley/SAM/Snell Kahuna K360 Tally Investigations

This is my attempts to reverse engineer the protocol.

Run as the following to spoof a Kahuna:
`./dumpdata <filename> | sudo nc -w 1 -kl -v -D 50009`

Run as the following to explore the data in the file:
`./dumpdata <filename> 1`
