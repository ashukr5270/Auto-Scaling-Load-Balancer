https://ap-south-1.console.aws.amazon.com/ec2/home?region=ap-south-1#AutoScalingGroupDetails:id=DemoAutoscaling;view=activity


![Image](

AWS:
Create a Launch Template: Define the blueprint for your EC2 instances (AMI, instance type, security group).
Create an Application Load Balancer (ALB): Set up a target group and a health check to monitor instance health.
Create an Auto Scaling Group (ASG): Link it to your launch template and the ALB's target group.
Configure Scaling Policies: Set rules for scaling, such as "add an instance if average CPU exceeds 70%" and 
"remove an instance if CPU drops below 30%."
