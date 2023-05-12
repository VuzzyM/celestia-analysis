# celestia-analysis

Celestia Data-Analysis: Is tool based on system resource monitor.

**This tool has the function of monitoring :** 

- the upload/download network
- server uptime
- server specifications
- information about ram memory usage
- information about server processes
- information about cpu consumption and disk usage.

**Web Framework & libraries**

**front end**
 - React.js
 - Chart.js
 
**back end**
 - Django
 - Psutil
 
 **Requirement python library:**
 
 ```pip install django```
 
 ```pip install psutil```

**Link**
[http://your_ip/domain:8000]

**Login Data**
 - username: your_username
 - password: your_password
 
 
 **Coommands for run this tool:**
 
 ```python manage.py migrate ```
 
 ```python manage.py runserver your_ip:8000 ```
 
 **Command for set username and password:**
 
 ```python3 manage.py createsuperuser```

 
 **Login Page:**
 
 ![3](https://github.com/VuzzyM/celestia-analysis/assets/66425682/75f9be93-d01d-4b7e-ac6e-0ddacb35b338)


**Analyze Celestia Node Server on different period:**

The time and date is in the corner of the image, the time zone is EEST.
I analyzed the celestia node for 3 days and here is the result.

The server's IP is censored in red, for security reasons.

**First day:**

The first day with version 0.9.3 the consumption shows an average of 10% cpu, the network sending/upload consumption is on average 600-1000 kB/s, the receive/download consumption is on average 650-800 kB /s. The ram memory is not much used.

![1-1](https://github.com/VuzzyM/celestia-analysis/assets/66425682/108f9982-063b-463c-aa00-ac37e37dac2b)
![1-2](https://github.com/VuzzyM/celestia-analysis/assets/66425682/e3b5a4a1-d15c-4ea0-90f1-67a7ff8db179)

The first day later with version 0.9.3 the consumption shows an average of 3% cpu, the sending/upload network consumption is on average 90-200 kB/s, the receive/download consumption is on average 50- 210 kb/s. The ram memory is not much used.

![2-1](https://github.com/VuzzyM/celestia-analysis/assets/66425682/70e9859c-8e06-4904-a9f6-2ec3225f07ab)
![2-2](https://github.com/VuzzyM/celestia-analysis/assets/66425682/bd5908cb-77a3-44ef-9668-f506878189f8)

**The next day:**

The next day with version 0.9.3 the consumption shows an average of 1-2% cpu, the network sending/upload consumption is on average 0-250 kB/s, the receive/download consumption is on average 0-25 kB /s. The ram memory is not much used.

![3-1](https://github.com/VuzzyM/celestia-analysis/assets/66425682/df94054a-5a33-4e09-a460-15e4726a1174)
![3-2](https://github.com/VuzzyM/celestia-analysis/assets/66425682/ae663a1c-c19a-4d22-aa42-71f7d3483cc7)

The next day later with version 0.9.3 the consumption shows an average of 1-2% cpu, the sending/upload network consumption is on average 60-100 kB/s, the receive/download consumption is on average 20- 25 kb/s. The ram memory is not much used.

![4-1](https://github.com/VuzzyM/celestia-analysis/assets/66425682/9d1f852d-f3e9-4093-a72a-57733524ffcc)
![4-2](https://github.com/VuzzyM/celestia-analysis/assets/66425682/467cdcf4-6f39-4bb4-8d57-4ab78057584f)

**Third day:**

The third day with version 0.9.4 the consumption shows an average of 3-4% cpu, the network sending/upload consumption is on average 200 kB/s, the receive/download consumption is on average 0-170 kB /s. The ram used virtual memory is 600 MB.

![5-1](https://github.com/VuzzyM/celestia-analysis/assets/66425682/d51da9aa-3c95-4eea-8821-8d4b5a4d4f4b)
![5-2](https://github.com/VuzzyM/celestia-analysis/assets/66425682/0ee58fd0-47fb-44d3-96d3-7eb8f2c86311)












