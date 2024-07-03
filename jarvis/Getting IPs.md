##### Tools for getting IPs

###### 1) ping -

Ping command is a general utility which is used for **checking whether any network is present and if a host is attainable** 

To chose your target
 - Suppose, Our target is 'facebook.com'. Gather information about 'facebook.com'.
Open terminal

```
   ~/Desktop $ ping target
```

For Example, target is etf.bg.ac.rs

```
	~/Desktop $ ping etf.bg.ac.rs
	Pinging etf.bg.ac.rs [147.91.14.197] with 32 bytes of data:
    Reply from 192.168.43.1: Destination net unreachable.
	Request timed out.
	Reply from 192.168.43.1: Destination net unreachable.
	Reply from 192.168.43.1: Destination net unreachable.
	
	Ping statistics for 147.91.14.197:
    Packets: Sent = 4, Received = 3, Lost = 1 (25% loss),

```

###### 2) nslookup -

```
	~/Desktop $ nslookup target
```

For Example, target is etf.bg.ac.rs

```
	~/Desktop $ nslookup etf.bg.ac.rs
	Server:  UnKnown
	Address:  192.168.43.1
	
	Non-authoritative answer:
	Name:    etf.bg.ac.rs
	Address:   147.91.14.197
```

###### 3) Some websites to find IPs of Target system

1) ipinfo.info
2) ipfinder.com
3) ipchecker.com
4) so one

This websites give not only IPs but also gives us bunch of information about target some information like modification date, actual address of serve locate, emails, etc information get from this websites.

###### 4) whois -

This tools not only gathering IPs but also provide bunch of information about Servers
just like above websites

```
	~/Desktop $ whois target
```


