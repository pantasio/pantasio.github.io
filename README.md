Site base on Hugo
theme: 

### How to use

```
echo "# show ip for hugo" >> ~/.bashrc
echo "IPADDRESS=$(ip addr show eth0 | grep "inet\b" | awk '{print $2}' | cut -d/ -f1)" >> ~/.bashrc
source ~/.bashrc
```

```
cd ~/pantasio.github.com/source-code/
hugo server --bind $IPADDRESS --baseURL=http://$IPADDRESS
```
## todo
- [ ] something in your eye
- [ ] ggwp


