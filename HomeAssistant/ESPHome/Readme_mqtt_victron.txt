ENABLE MQTT POOLING DIRECTLY FROM THE VICTRON CERBO OR SIMILAR.

-Menu Terminal
- cd ..
- cd share
- create folder: mosquitto
- cd mosquitto
- create file victron.conf
- nano victron.conf
- add the followin lines    
    connection venus-home
    address <local ip for the cerbo/raspberry>
    topic # both 0 venus-home/