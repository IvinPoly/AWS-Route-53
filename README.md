# AWS-Route-53
Created a basic website and hosted it using AWS S3 and AWS Route 53.
AWS Route 53 is a scalable and highly available Domain Name System (DNS) web service. It works by directing end users to internet applications by translating domain names (like www.example.com) into IP addresses (such as 192.0.2.1) that computers use to communicate with each other.
Key components:
1.Hosted Zone
2.DNS Records
3.Health Checks
How Route 53 Works:
Register Domain: You can register domain names directly through AWS or use external registrars.

Configure Hosted Zone: When you register a domain, Route 53 automatically creates a hosted zone for you, which is where you configure DNS records.

Resolve DNS Queries: When someone enters your domain name into a browser, Route 53 uses its global DNS network to resolve the domain name to the correct IP address using the DNS records in your hosted zone.

Traffic Routing: Based on the DNS records and the routing policies you define, Route 53 directs traffic to the appropriate endpoints, ensuring optimal performance and reliability.
