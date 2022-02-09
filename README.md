# wait_for_network.sh
simple bash script to wait for network

```
while [ "$(hostname -I)" = "" ]; do  
  echo -e "\e[1A\e[KNo network: $(date)"  
  sleep 1  
done  

echo "I have network";  
```
