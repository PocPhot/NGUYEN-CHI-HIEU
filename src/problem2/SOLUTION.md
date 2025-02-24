Provide your solution here:

- High availability
- Scalable
- Security
- Cost-effective
- 500 request/s
- Time to response < 100ms

*** Route 53 ***
- Function: Provide domain name for user access. 
- Replace: Can use DNS from third parner

*** WAF ***
- Function: Protect the web application from attack by blocking and filtering packets, IP
- Replace: Cloudflare WAF, Barracuda WAF

*** CloudFront ***
- Function: Improves read performance, content is cached at the edge. DDoS protection
- Replace: Cloudflare CDN

*** Internet Gateway ****
- Function: Allows resources in a VPC connect to the Internet
- Replace: AWS Direct Connect

*** Application Load Balancing ****
- Function: Load Balancing traffic
- Replace: We can build the nginx server by EC2

*** ECS Cluster ****
- Function: A Cluster is a group of services and tasks. It can scaling  when have hight request and switch traffic to other EC2 quickly
- Replace: Auto Scaling Group 

*** EC2 ****
- Function: Use ECS Agent and build the container
- Replace: EC2 normal or EKS

*** Aurora ****
- Function: It contain database, auto scaling and replicate
- Replace: RDS
