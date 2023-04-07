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