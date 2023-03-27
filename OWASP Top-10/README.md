# OWASP Top 10

This room breaks each OWASP topic down and includes details on what the vulnerability is, how it occurs and how you can exploit it. You will put the theory into practise by completing supporting challenges.


  - Injection
  - Broken Authentication
  - Sensitive Data Exposure
  - XML External Entity
  - Broken Access Control
  - Security Misconfiguration
  - Cross-site Scripting
  - Insecure Deserialization
  - Components with Known Vulnerabilities
  - Insufficent Logging & Monitoring

The room has been designed for beginners and assume no previous knowledge of security.


- Read the above.

	  no answer needed

- Connect to our network or deploy the AttackBox.

	  no answer needed

- I've understood Injection attacks.

	  no answer needed

- I've understood command injection.

	  no answer needed

- What strange text file is in the website root directory?

	- `ls`
	- `drpepper.txt`

- How many non-root/non-service/non-daemon users are there?

	- `cat /etc/passwd`
	- `0`

- What user is this app running as?

	- `whoami`
	- `www-data`

- What is the user's shell set as?

	- `cat /etc/passwd`
	- `/usr/sbin/nologin`

- What version of Ubuntu is running?

	- `lsb_release -a`
	- `18.04.4`

- Print out the MOTD.  What favorite beverage is shown?

	- `dr pepper`

- I've understood broken authentication mechanisms.

	  no answer needed

- What is the flag that you found in darren's account?

	- Register a user called ` darren` and then login is with that username.
	- `********************************`

- Now try to do the same trick and see if you can login as arthur.

	  no answer needed

- What is the flag that you found in arthur's account?

	- `********************************`

- Read the introduction to Sensitive Data Exposure and deploy the machine.

	  no answer needed

- Read and understand the supporting material on SQLite Databases.

	  no answer needed

- Read the supporting material about cracking hashes.

	  no answer needed

- What is the name of the mentioned directory?

	- `scilla dir -target http://<TARGET_IP>/` ([scilla](https://github.com/edoardottt/scilla))
	- `/assets`

- Navigate to the directory you found in question one. What file stands out as being likely to contain sensitive data?

	- `webapp.db`

- Use the supporting material to access the sensitive data. What is the password hash of the admin user?

	- `sqlite3 webapp.db`
	- `.tables`
	- `select * from users;`
	- `********************************`