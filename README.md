Prerequsite: 
Python Lib: aiocoap  

1. Clone the git repo 

git clone https://github.com/nikhilkomalan/thread-dfu-server-nRF5-SDK.git


2. Browse the project directory and execute the python script, the script will automaticaly get the PANID and Channel information :
 
  cd thread-dfu-server-nRF5-SDK/src/
  python3 main.py -f <firnware.zip> '<end device ipv6 addr>'
  
  For Eg.: 
  python3 main.py -f ota.zip 'fd0f:9505:d2d2:7961:171b:f828:409d:3ca3'
