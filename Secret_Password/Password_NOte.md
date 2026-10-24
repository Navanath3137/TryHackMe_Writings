┌──(kali㉿kali)-[~/THM]
└─$ ltrace ./Challenge_1609966715991.Challenge
printf("Insert your username: ")               = 22
__isoc99_scanf(0x564ef66ed01b, 0x7ffdd58e2390, 0, 0Insert your username: navanath
) = 1
strcpy(0x7ffdd58e2300, "navanath")             = 0x7ffdd58e2300
strcmp("navanath", "AGB6js5d9dkG7")            = 45
puts("\nAuthentication Error"
Authentication Error
)                 = 22
exit(0 <no return ...>
+++ exited (status 0) +++
                                                                             
┌──(kali㉿kali)-[~/THM]
└─$ ./Challenge_1609966715991.Challenge        
Insert your username: AGB6js5d9dkG7

Welcome
THM{65235128496} 
