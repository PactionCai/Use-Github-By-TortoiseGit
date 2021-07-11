# Use-Github-By-TortoiseGit
1. Download and then install git
	https://git-scm.com/download/win
	
2. Install TortoiseGit and its language package
	https://tortoisegit.org/download/
	
3. Configure TortoiseGit
	1) Configure username and password
		TortoiseGit -> Setting -> Git
		Input username and Email and then confirm
	2) Configure ssh client
		TortoiseGit -> Setting -> Network
		SSH client path need to be configured as C:\Program Files\Git\usr\bin\ssh.exe
		Apply -> Confirm

4. Generate key
	open git bash command line tool
	cd ~/.ssh and remove old keys
	ssh-keygen.exe -t rea -C "paction.cai@gmail.com"
	
5. Configure SSH key on Github
	https://github.com/settings/keys
	New SSH key
	Read the key from C:\Users\HP\.ssh\id_rsa.pub and then paste it to the new SSH key of Github