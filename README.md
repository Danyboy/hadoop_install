## Hadoop install

```bash
 hadoop_install -<i|h|a>
 Intsall hadoop on hosts or on a current machine

 example: # hadoop_install -i # for install hadoop on current machine
 example: # hadoop_install -a # for install hadoop on all machines in hosts file
```

### Hosts file example

```bash
10.10.10.11 test-01
10.10.10.12 test-02
10.10.10.13 test-03
#First line will be the master node. Needs empty string at the end of hosts file
```

### Пример запуска для установки на один хост в режиме мастера:

```bash
 ./hadoop_install -m
```

