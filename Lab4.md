### Task 1

Log on your raspberry pi as `pi`

**1. What command do you use to check the value of your IP address?**

```
ifconfig
```

**2. What is the IP address of your raspberry pi ethernet connection, the ethernet connection being the active one, the one connected to the Internet?**

```
10.50.11.32
```

**3. What is the MAC address of your raspberry pi ethernet connection?**

```
e4:5f:01:9c:3a:be
```

On your laptop:

**4. What command do you use to check the value of your IP address?**

```
ipconfig getifaddr en0
```

**5. What is the IP address of your laptop, the ethernet connection being the active one, the one connected to the Internet?**

```
10.70.132.132
```

**7. What is the MAC address of your laptop ethernet connection?**

```
36:de:87:7a:70:00
```



### Task 2

Troubleshooting the network layer (layer 3).

On the raspberry pi

- Use the ping command to ping :
  - your laptop using its IP address
  - localhost
- For each ping command, save the ping command and one reply in a text file **`lab4.txt`**, for example:
  - **`ping 192.168.0.16`**`: 64 bytes from 192.168.0.16: icmp_seq=1 ttl=64 time=9.21 ms`
- Use the ping command to ping `www.algonquincollege.com`

**8. What is IP address returned?**

​	

```
54.86.119.60
```



- In a web browser open the site `http://all-nettools.com/toolbox/smart-whois.php` and enter the previous IP in the Tectbox field .

**9. Who owns the IP address?**

```
Amazon EC2 Network Operations
```

**10. What class is this IP** (we'll cover that in class, but do a bit of research)

```
Class A.
```


