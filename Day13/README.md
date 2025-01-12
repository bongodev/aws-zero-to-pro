# **Day 13: AWS WAF and VPC Peering**
### Topic: Web Application Firewall (WAF) and Virtual Private Cloud (VPC) Peering
#### Guidelines:
- Learn how AWS WAF protects against common web exploits.
- Understand VPC architecture:
  - Subnets: Public and Private
  - Internet Gateways and NAT Gateways
  - Route Tables for managing traffic
  - VPC Peering for private communication between VPCs

#### Challenge:
1. Configure AWS WAF to block traffic from specific IP ranges and allow traffic only from your country.
2. Set up a VPC with the following components:
   - Two subnets (public and private).
   - Attach an Internet Gateway to the public subnet.
   - Configure a route table to connect the private subnet to the public subnet using a NAT Gateway.
3. Establish VPC peering between two VPCs in different regions and verify connectivity using EC2 instances in each VPC.
4. Create a LinkedIn post sharing what you’ve learned and your insights to inspire and support the community and fellow AWS enthusiasts.

#### Reference Links:
- [WAF Documentation](https://docs.aws.amazon.com/waf)
- [VPC Documentation](https://docs.aws.amazon.com/vpc)
- [VPC Peering Documentation](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html)