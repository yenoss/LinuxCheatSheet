# LinuxCheatSheet
for linxu newbie


## Ubuntu

### network
* netstat
  * find ports in use.
  ```
  netstat -tulpn
  ```
  
  
### bash
* echo $?
  * print previous [exitCode number]( https://www.tldp.org/LDP/abs/html/exitcodes.html).
 
### jq
* pretty json
~~~
sudo apt-get install jq
cat someText.txt | jq .
~~~
  
