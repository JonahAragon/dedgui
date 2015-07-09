#Manage Server Configuration


![](http://i.imgur.com/UDPur6R.png)
DEDGui allows server administrators to edit the servers starting resource values and configuration.
The configuration options are rather self explantory.

For the Save Method you have 3 options. h2, h2-server and none. 
  h2 is the default which means the database can only be used by 1 process at a time
  h2-server means the database can be used by multiple processes at a time but affects speed a bit
  none means that there is no save method and anything the client does won't be saved.
  
For DNS Enabled you can either set it to true or fale. For DNS Mode, Remote means worldwide and local means your network using your local IP address (eg, 192.168.1.10).

For more information on DNS [click here](DNS.MD)
