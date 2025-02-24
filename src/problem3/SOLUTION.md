Provide your solution here:

*** Find the reason ***
Step 1: Check memory using - ![alt text](image.png)
- Use CLI: "free -h" to check memory using present.

Step 2: Check process of aplication - ![alt text](image-1.png)
- Use comment 'top'

Step 3: Check log at path ./var/log/nginx - ![alt text](image-2.png)
- Check file log.access and log.error
- Check count of request from log file -> Maybe DDoS attacker

*** Solution ***
Solution 1: Auto-reboot scheduler configuration for Nginx.
Solution 2: Upgrade resource if necessary
