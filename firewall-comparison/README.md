# Open-Source Firewalls - Comparisons (Project)

Tested three open-source firewalls in a group of 3 to examine the effectiveness of the firewalls

We compared and contrasted the 2-3 firewalls

We then collated and analysed the results of our testings

For my individual work in this project, I was testing 'pfSense' firewall
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/151bc63b-227a-44ca-8420-35ce2a46a5eb" />

Here, I launched pfSense through a VM in my system, and works well in Oracle VirtualBox

To confirm the firewall access, I pinged the LAN IP address from pfSense in Ubuntu to see if they are connected

<img width="626" height="200" alt="image" src="https://github.com/user-attachments/assets/6fd3e220-9b9d-4e15-bc6a-2c3b9c6faf9a" />


I filtered traffic by creating custom firewall rules and NAT policies to block unauthorized inbound traffic while allowing safe outbound connections. I was also using the VirtualBox VM shown here to edit rules

<img width="624" height="342" alt="image" src="https://github.com/user-attachments/assets/7dcb8057-1e00-4c0a-a79a-5f257d5b885f" />

<img width="625" height="104" alt="image" src="https://github.com/user-attachments/assets/6e8f2e46-fc97-4ef0-b9f0-f806dc95f892" />

Then I tried to ping Google, and it took too much time and failed eventually, which shows that pfSense has blocked outgoing traffic and the rule worked successfully
