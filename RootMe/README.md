# RootMe


- Deploy the machine

	no answer needed

- Scan the machine, how many ports are open?

	- `nmap <TARGET_IP>`
	- `2`

- What version of Apache are running?

	- `nmap -sV <TARGET_IP>`
	- `2.4.29`

- What service is running on port 22?

	- `ssh`

- Find directories on the web server using the GoBuster tool.

	no answer needed

	- `gobuster dir -u http://<TARGET_IP>/ -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt`

- What is the hidden directory?

	- `/panel/`