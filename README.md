# Zabbix-My-Templattes
My templates for Zabbix

Scrutiny template Config Macro:
My AnalogJ Scrutiny Template for Zabbix with proxmox support for power off servers to not showing alerts when server is powered off - macro:
{$ALERT_LEVEL} 0 - all, 1 - SMART, 2 - SCRUTINY
{$PROXMOX_API_HOST} https://xxxx:8006
{$PROXMOX_API_KEY} proxmox api key
{$PROXMOX_API_SECRET} proxmox api secret
{$SCRUTINY_API_HOST} http://xxx without / in end | is support hosts who not have proxmox
