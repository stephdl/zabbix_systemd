# Systemd template for Zabbix Agent 2
### Features:

- Automatic discovery systemd units
- Monitor service status
- Adapted to NethServer

The disable services are not monitored, Zabbix creates alerts with HIGH status for enabled service in a stopped state. If you do not need the monitoring of a service you can disabled it.

### Configure the Zabbix Server
1. Import the template file into Zabbix Server (this operation is done only once). Use the template file that matches your Zabbix Server version. (Template_Systemd.xml minimal requirements is 5.0.6 or 5.2.2). Go to https://raw.githubusercontent.com/stephdl/zabbix_systemd/master/Template_Systemd.xml and save by 'ctrl+s'

2. Assign the template to a host that you want to monitor.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=GEH7YJEBWTFWE&currency_code=USD&source=url)
