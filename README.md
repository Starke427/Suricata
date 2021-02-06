# Suricata
Automate Suricata installation on CentOS 7. It's recommended that you run this on a fresh install that has been provisioned with two network interfaces; one for network access and one to dedicate to a SPAN port. 

---

The easiest way to download this is to curl the output to a local file.

Optionally, as an argument, specify the interface you would like to use. If no interface is specified it will use the first available. Example: ./suricata_setup.sh ens160

```
curl https://raw.githubusercontent.com/Starke427/Suricata/master/suricata_setup.sh > suricata_setup.sh

chmod 700 suricata_setup.sh

./suricata_setup.sh   

```
