# Configuring iptables
<br />

### *** Redirect a request from the web to an internal ip address based on port (IE: openstack) ***

iptables -t nat -A PREROUTING -p tcp --dport SOURCE_PORT -j DNAT --to-destination DESTINATION_IP:DESTINATION_PORT
iptables -t nat -A PREROUTING -p tcp --dport 3000 -j DNAT --to-destination 10.0.0.4:3000

A system reboot will wipe any unsaved configuration.

Related resources:
http://www.debuntu.org/how-to-redirecting-network-traffic-to-a-new-ip-using-iptables/
http://www.fclose.com/816/port-forwarding-using-iptables/
http://www.linuxquestions.org/questions/linux-security-4/iptables-prerouting-chain-not-working-for-me-696734/
http://www.cyberciti.biz/faq/howto-display-linux-iptables-loaded-rules/
http://linuxcommando.blogspot.com/2008/05/how-to-display-routing-table.html
http://major.io/2007/02/09/delete-single-iptables-rules/
http://forums.fedoraforum.org/showthread.php?t=196263
http://blog.softlayer.com/2011/iptables-tips-and-tricks-port-redirection/
