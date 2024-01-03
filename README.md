# Tableau_Log4J_RCE
Remote Code Execution via Log4J via Insecure Deserialization in Vulnerable Instances of "Tableau Server". 

Remote Code Execution in many Log4J proof of concepts leverages the ability for Java to load a remote class. However after JRE version 11.0.1, Remote Class Loading is disabled by default.

We were able to exploit a unpatched Log4J instances within vulnerable (also unpatched) Tableau Servers with another method instead - insecure deserializion.
