# Elf McEager becomes CyberElf

For Server provide (<TARGET_IP>) as the IP address provided to you for the remote machine. The credentials for the user account is:

  - User name: `Administrator`
  - User password: `sn0wF!akes!!!`

So then let's connect ourselves to the remote machine using Remmina.

We'll use [CyberChef](https://gchq.github.io/CyberChef/) also.

- What is the password to the KeePass database?
	
	- Open the `dGhlZ3J*******FzaGVyZQ==` folder, then executes the Keepass executable and try to enter the password `mceagerrockstar`. Wrong.
	- Open CyberCher and try to decode the folder name.
	- Put `dGhlZ3J*******FzaGVyZQ==` in the Input panel and add to recipe `Magic`. It's probably Base64.
	- `**************re`
	- Let's enter the password inside Keepass.

- What is the encoding method listed as the 'Matching ops'?

	- You an see this in output panel
	- `Base64`

- What is the decoded password value of the Elf Server?

	- Navigate into Network tab (in Keepass).
	- Double click on the unique entry.
	- Click on the button to see the password without bullets, read the notes below.
	- Paste this in input on CyberChef.
	- Use the recipe `From Hex`.
	- `********`

- What is the decoded password value for ElfMail?

	- Switch Keepass tab to see eMail entries.
	- Copy the elfMail password and read the notes.
	- `&#105;****;&#51;&#83;*****;&#97;*****;&#105*******&#103;&excl;`
	- Paste this input in CyberChef with recipe `From HTML Entity`.
	- `********ng!`

