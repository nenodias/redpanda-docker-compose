# redpanda docker-compose example

### Before use it you should set aio-max-nr to 1048576
#### To set the aio-max-nr value, add the following line to the /etc/sysctl.conf file:
```fs.aio-max-nr = 1048576```
#### To activate the new setting, run the following command:
```sysctl -p /etc/sysctl.conf```

### Now you can just run
```docker compose up```

### Enjoy your redpanda/kafka