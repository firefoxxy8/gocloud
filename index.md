---
layout: default
---

![](https://cdn-images-1.medium.com/max/400/1*9O2rQPRYCkAP3AHBb2QQww.png)

GoCloud is a golang library which hides differences between different cloud providers' (AWS,GCP,Openstack etc) APIs and allows you to manage different cloud resources through a unified and easy to use API.

_Fork me!_
```
git clone https://github.com/cloudlibz/gocloud.git
```

## [Service Types](#header-2)

**Compute**  --Allows you to manage cloud and virtual servers.

**Compute Storage**  --Allows you to manage Compute storage.

**Container**  --Allows users to install and deploy containers onto container based virtualization platforms.

**Load balancer**  --Allows you to manager Load Balancer service.

**DNS**  --Allows you to manage DNS service.

## [Service Providers](#header-2)

### [AWS](#header-3)

- EC2 (Compute)
- EC2 Storage
- Amazon Elastic Container Service (Container)
- Elastic Load Balancing
- AWS Route53

### [Google](#header-3)

- Google Compute
- Google Compute Storage
- Google  Container Service (Container)
- Google Elastic Load Balancing 
- Google DNS 

Currently, implementaions for other cloud providers are being worked on.
