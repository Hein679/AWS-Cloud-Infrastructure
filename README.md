# Scalable infrastructure using AWS Cloud

Link to [diagram](https://miro.com/app/board/uXjVNhM6xNM=/?share_link_id=567410157721)

![](./FinalArchitecture.png)

## Summary
<div style="text-align: justify">
The diagram illustrates an architectural blueprint for building scalable web applications across multiple availability zones, leveraging core AWS services for optimal performance and cost-efficiency. The core components include Amazon <b>VPC</b>, <b>EC2</b>, <b>Aurora (RDS)</b> and <b>S3</b>. <br><br>
Amazon VPC (Virtual Private Cloud) for facilitating network segmentation, resource isolation and enhancing security through the utilization of public and private subnets. <br><br>
EC2 (Elastic Compute Cloud) offers vertically scalable computing resources on demand. This is further complemented by the integration of ALB (Application Load Balancing) and ASG (Auto Scaling Group), providing control and configurations for horizontal scaling, enabling adjustments to varying workloads, ensuring high availability and fault tolerance.
<br><br>
Aurora (RDS) for a high-performance RDBMS, delivering redundancy, reliability, scalability and features such as backup & backtrack through RDS Snapshots. <br><br>
S3 (Simple Storage Service) serves as a simple and robust solution for storing various data types, including static web content, ensuring seamless integration and interconnectivity within applications.
</div>