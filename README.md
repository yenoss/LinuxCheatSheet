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
  
  
## VIM

### Widnow
* Split
  * :vsp
  * :sp

### Window Focusing
* Shift focus to direction of current. 
  * ctrl + w +  h,j,k,l 

### Window Resizing
* :res +5 or -5 
* :vertical res +5 -5 

### Using mouse
* :set mouse=a

## NerdTree
* FileSystem mode
  * m + a  => new node
