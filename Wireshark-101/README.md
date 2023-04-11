# Wireshark 101

- Read the above and move on to Installation.

	  no answer needed

- Read the above, and ensure you have Wireshark installed.

	  no answer needed

- Read the above and play around with Wireshark.

	  no answer needed

- Read the above and practice collecting captures, as well as understand the various capture techniques available

	  no answer needed

- Read the above and understand the basics of packet filtering.

	  no answer needed

- Read the above and move on to analyzing application protocols.

	  no answer needed

- What is the Opcode for Packet 6?

	- `request (1)`

- What 4 packets are Reply packets?

	- Apply as filter: `arp.opcode==2`
	- `**,***,***,***`

- What IP Address is at `80:fb:06:f0:45:d7`?

	- The first found previously (`**`).

- What is the type for packet 4?

	- `8`

- What is the type for packet 5?

	- `0`

- What is the timestamp for packet 12, only including month day and year? note: Wireshark bases it’s time off of your devices time zone, if your answer is wrong try one day more or less.
	
	- `May **, 2013`

- What is the full data string for packet 18?

	- `08090a0b0c0d0e0f101112131415161718191a1b1c1d1e1f202122232425262728292a2b2c2d2e2f303132*********`

- Read the above and move into Task 10.

	  no answer needed

- What is being queried in packet 1?

	- `*.*.*.*.in-addr.arpa`

- What site is being queried in packet 26?

	- `www.********.org`

- What is the Transaction ID for packet 26?

	- `0x**58`

- What percent of packets originate from Domain Name System?

	- Into `Statistics` tab
	- `4.7`