# Oracle-WLS-Weblogic-RCE
(CVE-2019-2725) Oracle WLS(Weblogic) RCE test sciript

CVE-2019-2725 is a deserialization vulnerability in Oracle WebLogic Server. This remote code execution vulnerability is remotely exploitable without authentication. 

This script which check the presence or absence of a page is based on Python2. 

Usage>

    python Oracle WLS(Weblogic) RCE(CVE-2019-2725).py <dst_ip> <dst_port> (user defined port)
    
    python Oracle WLS(Weblogic) RCE(CVE-2019-2725).py <dst_ip> (default : 80/tcp)
       
