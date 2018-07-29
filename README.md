# distributed
## 资源服务器
AWS云服务器 
Amazon Linux AMI 2018.03.0 (HVM), SSD Volume Type - ami-cfe4b2b0 
Amazon Linux AMI 是一个 EBS 与 AWS 支持的映像。默认映像包括 AWS 命令行工具、Python、Ruby、Perl、和 Java。存储库包括 Docker、 PHP、 MySQL、 PostgreSQL 和其他软件包。 

1. server1  公有 DNS (IPv4):  ec2-34-239-118-33.compute-1.amazonaws.com    IPv4 公有 IP: 34.239.118.33
2. server2  公有 DNS (IPv4):  ec2-18-212-187-159.compute-1.amazonaws.com   IPv4 公有 IP: 18.212.187.159
3. server3  公有 DNS (IPv4):  ec2-174-129-75-216.compute-1.amazonaws.com   IPv4 公有 IP: 174.129.75.216


* ssh -i 'C:\Users\Arlen\.ssh\homekeypari.pem'  ec2-user@34.239.118.33
* ssh -i 'C:\Users\Arlen\.ssh\homekeypari.pem'  ec2-user@18.212.187.159
* ssh -i 'C:\Users\Arlen\.ssh\homekeypari.pem'  ec2-user@174.129.75.216

* ssh   ec2-user@34.239.118.33
* ssh   ec2-user@18.212.187.159
* ssh   ec2-user@174.129.75.216



