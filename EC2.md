# Amazon Elastic Cloud Compute (EC2) Notes 

## Date: [05/22/2024]

---

## What is Amazon Elastic Compute Cloud (Amazon EC2) virtualization?

### Overview:

- EC2 instances run as virtual machines on host computers that are located in AWS Availability Zones. 
- Applications can be install and run on the OS (Linux or Windows) in each virtual machine. 
- The virtual machines run on top of a **hypervisor** layer that AWS maintains.
- **Hypervisor**: the operating platform layer that provides the EC2 instances with access to the actual hardware (processors, memory, and storage) that the instances need to run.
- Each EC2 is given a certain number of virtual CPUs for processing and RAM for memory. 
- Some instances use ephermeral storage (instance store) that is physically attached to the host computer and provides temporary block-level storage for use with an instance.
- The data in an instance store persists only during the lifetime of the instance that uses it. If rebooted, data persists. If stopped or terminate, data is lost and unable to recover. 

### EC2 instance network connectivity:

- EC2 instances can connect to other resources over a network. 
- EC2 instances can also connect to the internet, other EC2 instances, and Amazon S3 object storage buckets.
- Some instances use Amazon Elastic Block Storage (EBS) instead of ephermeral storage. Amazon EBS provides persistent block storage volumes, which means that the data will be persisted, even when the instance is in a stopped state. These instances minimize I/O contention between EBS and other traffic, which means better performance. 

---

## How to launch an EC2 instance:

### Subtopic A

- Point 1
- Point 2

### What is Amazon Machine Image (AMI)?

- Provides the information that us needed to launch an instance. You can launch multiple instances from a single AMI when you need multiple instances with the same configuration. 
- Point 2

---

## Best Practices:

- [ ] Task 1
- [ ] Task 2
- [ ] Task 3

---

## Key Takeaways

- Key takeaway 1
- Key takeaway 2

---

## Questions

- Question 1
- Question 2

---

## Next Steps

- Next step 1
- Next step 2


