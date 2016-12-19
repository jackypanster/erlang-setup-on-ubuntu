### How to install erlang on ubuntu

+ Install dependencies

```bash
sudo apt-get install build-essential libncurses5-dev openssl libssl-dev fop xsltproc unixodbc-dev
```

+ Download source code of erlang
```bash
http://erlang.org/download/otp_src_19.2.tar.gz
tar zxvf otp_src_19.2.tar.gz
cd otp_src_19.2
```

+ Configurate and compile the source code of erlang
```bash
./configure && make && sudo make install
```
