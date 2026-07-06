EC2 - Elastic Compute Cloud

Configuration Options For EC2
1. Operating System
2. Compute Power
3. RAM
4. Storage space and which type
5. Network card 
6. Firewall rules : security group
7. Bootstrap script  (Launch commands while machine starts and runs  only ones when machine starts)

- Bootstrap script runs with root user privilege
- Security group controls traffic from and to to our instance
- When an instance is stopped and started again it get new public ip addr but private public ip addr remains same
- private ip addr is used to ssh in instance from aws console i.e. private network