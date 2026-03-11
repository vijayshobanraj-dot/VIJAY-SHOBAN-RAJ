VIJAY-SHOBAN-RAJ

How many email addresses were discovered?
theHarvester -d hacker.org -b bing  
Read proxies.yaml from /etc/theHarvester/proxies.yaml
*******************************************************************
*  _   _                                            _             *
* | |_| |__   ___    /\  /\__ _ _ ____   _____  ___| |_ ___ _ __  *
* | __|  _ \ / _ \  / /_/ / _` | '__\ \ / / _ \/ __| __/ _ \ '__| *
* | |_| | | |  __/ / __  / (_| | |   \ V /  __/\__ \ ||  __/ |    *
*  \__|_| |_|\___| \/ /_/ \__,_|_|    \_/ \___||___/\__\___|_|    *
*                                                                 *
* theHarvester 4.8.2                                              *
* Coded by Christian Martorella                                   *
* Edge-Security Research                                          *
* cmartorella@edge-security.com                                   *
*                                                                 *
*******************************************************************

[*] Target: hacker.org 

Read api-keys.yaml from /etc/theHarvester/api-keys.yaml
        Searching 0 results.
[*] Searching Bing. 

[*] No IPs found.

[*] No emails found.

[*] No people found.



[*] No hosts found.
----------------------------------------------------------------------------------------
How many devices are active?
nmap hackthissite.org
Starting Nmap 7.95 ( https://nmap.org ) at 2026-03-11 23:02 IST
Nmap scan report for hackthissite.org (137.74.187.102)
Host is up (0.087s latency).
Other addresses for hackthissite.org (not scanned): 64:ff9b::894a:bb64 64:ff9b::894a:bb67 64:ff9b::894a:bb66 64:ff9b::894a:bb68 64:ff9b::894a:bb65 137.74.187.104 137.74.187.101 137.74.187.100 137.74.187.103
Not shown: 997 filtered tcp ports (no-response)
PORT    STATE  SERVICE
22/tcp  closed ssh
80/tcp  open   http
443/tcp open   https
------------------------------------------------------------------------------------------------
What is the mail server (MX record)? How many email addresses were discovered?
Mail (MX) Servers:
___________________

aspmx5.googlemail.com.                   293      IN    A        142.250.101.26
alt1.aspmx.l.google.com.                 293      IN    A        172.217.221.27
aspmx4.googlemail.com.                   293      IN    A        172.217.78.26
alt2.aspmx.l.google.com.                 293      IN    A        172.217.221.26
aspmx2.googlemail.com.                   293      IN    A        172.217.221.26
aspmx.l.google.com.                      293      IN    A        142.250.4.27
aspmx3.googlemail.com.                   293      IN    A        192.178.163.26
------------------------------------------------------------------------------------------------
What is the gateway IP?
route -n
Kernel IP routing table
Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
0.0.0.0         172.21.187.203  0.0.0.0         UG    100    0        0 eth0
172.21.187.0    0.0.0.0         255.255.255.0   U     100    0        0 eth0
------------------------------------------------------------------------------------------------
What is the main IP address of the domain?
nslookup hackthissite.org
Server:         172.21.187.203
Address:        172.21.187.203#53

Non-authoritative answer:
Name:   hackthissite.org
Address: 137.74.187.103
Name:   hackthissite.org
Address: 137.74.187.100
Name:   hackthissite.org
Address: 137.74.187.101
Name:   hackthissite.org
Address: 137.74.187.104
Name:   hackthissite.org
Address: 137.74.187.102
Name:   hackthissite.org
Address: 64:ff9b::894a:bb65
Name:   hackthissite.org
Address: 64:ff9b::894a:bb68
Name:   hackthissite.org
Address: 64:ff9b::894a:bb66
Name:   hackthissite.org
Address: 64:ff9b::894a:bb67
Name:   hackthissite.org
Address: 64:ff9b::894a:bb64
------------------------------------------------------------------------------------------------
1.	Who is the domain registrar?2.	When was the domain created?
Domain Name: hackthissite.org
Registry Domain ID: REDACTED
Registrar WHOIS Server: http://whois.porkbun.com
Registrar URL: https://porkbun.com
Updated Date: 2025-07-15T23:08:30Z
Creation Date: 2003-08-10T15:01:25Z
Registry Expiry Date: 2026-08-10T15:01:25Z
Registrar: Porkbun LLC
Registrar IANA ID: 1861
Registrar Abuse Contact Email: abuse@porkbun.com
Registrar Abuse Contact Phone: +1.8557675286
Domain Status: clientDeleteProhibited https://icann.org/epp#clientDeleteProhibited
Domain Status: clientTransferProhibited https://icann.org/epp#clientTransferProhibited
Name Server: c.ns.buddyns.com
Name Server: f.ns.buddyns.com
Name Server: g.ns.buddyns.com
Name Server: h.ns.buddyns.com
Name Server: j.ns.buddyns.com
DNSSEC: unsigned
URL of the ICANN Whois Inaccuracy Complaint Form: https://icann.org/wicf/
>>> Last update of WHOIS database: 2026-03-11T17:48:42Z <<<

For more information on Whois status codes, please visit https://icann.org/epp

Terms of Use: Access to Public Interest Registry WHOIS information is provided to assist persons in determining the contents of a domain name registration record in the Public Interest Registry registry database. The data in this record is provided by Public Interest Registry for informational purposes only, and Public Interest Registry does not guarantee its accuracy. This service is intended only for query-based access. You agree that you will use this data only for lawful purposes and that, under no circumstances will you use this data to (a) allow, enable, or otherwise support the transmission by e-mail, telephone, or facsimile of mass unsolicited, commercial advertising or solicitations to entities other than the data recipient's own existing customers; or (b) enable high volume, automated, electronic processes that send queries or data to the systems of Registry Operator, a Registrar, or Identity Digital except as reasonably necessary to register domain names or modify existing registrations. All rights reserved. Public Interest Registry reserves the right to modify these terms at any time. By submitting this query, you agree to abide by this policy.  The Registrar of Record identified in this output may have an RDDS service that can be queried for additional information on how to contact the Registrant, Admin, or Tech contact of the queried domain name.
------------------------------------------------------------------------------------------------
Is a WAF present?
wafw00f hackthissite.org

                 ?              ,.   (   .      )        .      "
         __        ??          ("     )  )'     ,'        )  . (`     '`
    (___()'`;   ???          .; )  ' (( (" )    ;(,     ((  (  ;)  "  )")
    /,___ /`                 _"., ,._'_.,)_(..,( . )_  _' )_') (. _..( ' )
    \\   \\                 |____|____|____|____|____|____|____|____|____|

                                ~ WAFW00F : v2.3.1 ~
                    ~ Sniffing Web Application Firewalls since 2014 ~

[*] Checking https://hackthissite.org
[+] Generic Detection results:
[-] No WAF detected by the generic detection
[~] Number of requests: 7
------------------------------------------------------------------------------------------------
who is the vendor ?
there no vendor because there is no WAF used
------------------------------------------------------------------------------------------------
