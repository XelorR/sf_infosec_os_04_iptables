# Homework with iptables basics

## Rule

```bash
sudo iptables -A INPUT -p icmp -j REJECT
```

rule screenshot here

## Fail

ping fail after rule restriction here

## Revert

```bash
sudo iptables -L
```

screenshot with rules here

```bash
sudo iptables -D INPUT 2
```

reverting to initial config and screenshot with ping working here
