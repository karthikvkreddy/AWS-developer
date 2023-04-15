## Pricing Model:
1. On Demand
    - pay by the hour or second depending on the type of instance you run
2. Reserved
    - reserved for 1 or 3 years. Upto 72% of discount on the hourly charge 
    - regional
3. Spot
    - Purchase unused capacity at a discount of up to 90%
    - prices flucuate with supply and demand. 
4. dedicated
    - physical EC2 server dedicated for your instance.
    - the most expensive option

### 1. ON DEMAND INSTANCES:
- Flexible
    - Low cost and flexibility of Amazon EC2 without any up-front payment or longterm commitment
- Short-Term 
    - Applications with short-term, spiky, or unpredictable workloads that cannot be interrupted
- Testing the Water
    - Applications being developed or tested on Amazon EC2 for the first time.

### 2. Reserved Instances:
- Predictable Usage
    - Applications with steady state or predictable usage.
- Specific Capacity Requirements
    - Applications that require reserved capacity.
- Pay up front
    - You can make up-front payments to reduce the total computing costs even further
- standard RIs
    - Up to 72% off the on-demand price.
- convertable RIs
    - Up to 54% off the on-demand price. Has the option to change to a different RI type of equal or greater value.
- Scheduled RIs
    - Launch within the time window you define. Match your capacity reservation to a predictable recurring schedule that only requires a fraction of a day, week, or month
    - eg. electricity bill generator

### 3. Spot Instances:
- When To Use Spot Instances ?
    - Flexible: 
        - When To Use Spot Instances
    - Urgent capacity:
        - Users with an urgent need for large amounts of additional computing capacity 
        - Image rendering
    - Cost Sensitive:
        - Applications that are only feasible at very low compute prices

### 4. Dedicated Instances:
- Compliance
    - Regulatory requirements that may not support multi-tenant virtualization.
- On-Demand
    - Can be purchased on-demand (hourly).
- Licensing
    - Great for licensing which does not support multi-tenancy or cloud deployments.
- Reserved
    - Can be purchased as a reservation for up to 70% off the on-demand price. 

### Savings Plans
- Save up to 72%
    - All AWS Compute usage regardless of instance type or Region.
- Commit to One or Three Years 
    - Commit to use a specific amount of compute power (measured in $/hour) for a one-year or three-year period. 
- Super flexible:
    - Not only EC2, this also includes serverless technologies like Lambda and Fargate. 

### Usefull Links:
- AWS Pricing Calculator: https://calculator.aws

### EBS Volumes:
 