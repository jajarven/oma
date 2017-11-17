
enum4linux 10.10.10.40

...

smbclient -L 10.10.10.40

OS=[Windows 7 Professional 7601 Service Pack 1] Server=[Windows 7 Professional 6.1]

	Sharename       Type      Comment
	---------       ----      -------
	ADMIN$          Disk      Remote Admin
	C$              Disk      Default share
	IPC$            IPC       Remote IPC
	Share           Disk      
	Users           Disk
  
smbclient \\\\10.10.10.40\\users 


