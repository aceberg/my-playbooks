### Init
```
incus admin init
```

### Port forwarding
```
incus config device add deb12 port-10022-ssh proxy listen=tcp:0.0.0.0:10022 connect=tcp:127.0.0.1:22
```

### Network problem fix
```
cat /etc/sysctl.d/40-forward.conf
net.ipv4.ip_forward=1
```
