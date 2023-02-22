# Amazon Elastic Compute Cloud (Amazon EC2)

    Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud.
    It is designed to make web-scale cloud computing easier for developers.

## How does Amazon EC2 work?

1. Launch an instance (a virtual server in the cloud)
2. Connect to the instance
3. Use the instance (install software, run applications, etc.)

## Amazon EC2 instance types

### General purpose instances

    provides a balance of compute, memory, and network resources and is a good choice for most workloads 

* application servers
* web servers
* gaming servers
* backend servers
* small and medium databases

### Compute optimized instances

    provides a high level of compute resources and is a good choice for workloads that require high performance processors.

* compute-intensive applications
* batch processing
* high performance web servers
* distributed analytics

### Memory optimized instances

    provides a high level of memory and is a good choice for workloads that require high performance processors and high amounts of memory.

### Accelerated computing instances

    provides a high level of GPU compute power and is a good choice for workloads that require graphics-intensive applications, such as video encoding, 3D modeling, and image processing.

### Storage optimized instances

    provides a high level of local, temporary storage and is a good choice for workloads that require high, sequential read and write access to large data sets on local storage.

## Amazon EC2 pricing

### On-Demand Instances

### Amazon EC2 Savings Plans

### Reserved Instances

### Spot Instances

### Dedicated Hosts

# Scalability

    Scalability is the measure of a system’s ability to increase or decrease in performance and cost in response to changes in application and system processing demands. 

## Scaling Amazon EC2 (Auto Scaling)

    Auto Scaling helps you ensure that you have the correct number of Amazon EC2 instances available to handle the load for your application.
    You can use Auto Scaling to help ensure that you do not exceed your Amazon EC2 costs or that your application has enough capacity to handle the expected load.

### Dynamic scaling

    enables you to automatically add or remove Amazon EC2 instances based on a scaling policy that you define.
    For example, you can configure Auto Scaling to automatically add Amazon EC2 instances when the average CPU utilization for your application exceeds a specified threshold.

### Predictive scaling

    enables you to automatically add or remove Amazon EC2 instances based on a forecast of your application’s future load.
    For example, you can configure Auto Scaling to automatically add Amazon EC2 instances when the forecasted CPU utilization for your application exceeds a specified threshold.

# Elastic Load Balancing

        Elastic Load Balancing automatically distributes incoming application traffic across multiple targets such as Amazon EC2 instances, containers, and IP addresses.
        It can handle the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones.
        You can use Elastic Load Balancing to improve the availability and scalability of your application.

