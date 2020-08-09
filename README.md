# RabbitMQ Installation

## Manual Installation 

1. Erlang is a dependency which is needed for RabbitMQ.

```
# yum install https://packages.erlang-solutions.com/erlang/rpm/centos/7/x86_64/esl-erlang_22.2.1-1~centos~7_amd64.rpm -y 
```

2. Setup YUM repositories for RabbitMQ.

```
# curl -s https://packagecloud.io/install/repositories/rabbitmq/rabbitmq-server/script.rpm.sh | sudo bash
```

3. Install RabbitMQ 

```
# yum install rabbitmq-server -y 
```

4. Start RabbitMQ 

```
# systemctl enable rabbitmq-server 
# systemctl start rabbitmq-server 
```


## Install with Script 

```
# curl -s https://raw.githubusercontent.com/linuxautomations/labautomation/master/tools/rabbitmq/install.sh | bash 
```


RabbitMQ comes with a default username / password as `guest`/`guest`.

