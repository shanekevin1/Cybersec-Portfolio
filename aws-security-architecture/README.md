This project is based on a fictitious scenario; redesigns the infrastructure for 'WinLocal Giveaways', a small startup specializing in online competitions and promotional giveaways. They follow a major ransomware incident caused by a flat network architecture and limitations (e.g. outdated load balancers, frequent storage outages)

This cloud architecture relates directly to AWS as part of this project I did

<img width="304" height="639" alt="image" src="https://github.com/user-attachments/assets/5343316a-6e4a-49ad-8cca-69e72183fe47" />

My architecture diagram above shows the cloud solution I designed for WinLocal. I organized everything into three separate layers - public, private, and data. I did this because WinLocal's previous flat network allowed ransomware to spread easily. My design stops that completely

I implemented solutions such as: 

Segmenting the Network (VPC)- built isolated Public Subnets (for web servers) and Private Subnets (for the backend database), using a Bastion Host with strict SSH rules so private servers are never exposed to the internet

<img width="622" height="173" alt="image" src="https://github.com/user-attachments/assets/140564b8-7aba-43e4-bec0-9494dfd60d0b" />
<img width="502" height="622" alt="image" src="https://github.com/user-attachments/assets/3d298c9b-dc61-4f2c-a72b-d6f501aef4b3" />

