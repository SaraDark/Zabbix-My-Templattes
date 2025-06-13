# Zabbix-My-Templattes
My templates for Zabbix
<br>
<br>
# Scrutiny template Config Macro:<br>
- My AnalogJ Scrutiny Template for Zabbix with proxmox support for power off servers to not showing alerts when server is powered off - macro:<br>
{$ALERT_LEVEL} 0 - all, 1 - SMART, 2 - SCRUTINY<br>
{$PROXMOX_API_HOST} https://xxxx:8006<br>
{$PROXMOX_API_KEY} proxmox api key<br>
{$PROXMOX_API_SECRET} proxmox api secret<br>
{$SCRUTINY_API_HOST} http://xxx without / in end | is support hosts who not have proxmox<br>
