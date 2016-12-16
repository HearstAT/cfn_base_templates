# Cloudformation Baseline Templates

Our base templates for CentOS, Ubuntu, and Amazon Linux

## What's in a Base Image?

### Default Parameters

-   Instance Type
-   VPC
-   KeyName
-   SSHSecurityGroup
-   CIDRA (Set CIDR for Public Subnet)
-   CIDRB (Auto-scaled templates only)

### Autoscale Specific Parameters

-   InstanceMaxCount
-   InstanceMinCount

### Ubuntu
-   OS: 16.04 Xenial [AMI List](https://cloud-images.ubuntu.com/locator/ec2/)
-   APT Packages:
    -   wget
    -   curl
    -   python-setuptools
    -   python-pip
    -   git
-   Other Packages:
    -   Python Pip
    -   CFN Bootstrap Tools

### CentOS
-   OS: Centos 7 [AMI List](https://aws.amazon.com/marketplace/pp/B00O7WM7QW)
-   YUM Packages:
    -   wget
    -   curl
    -   python-setuptools
    -   git
-   Other Packages:
    -   Python Pip
    -   CFN Bootstrap Tools

### Amazon Linux
-   OS: Amazon Linux 2016.09.0 [AMI List](https://aws.amazon.com/amazon-linux-ami/)
-   YUM Packages:
    -   wget
    -   curl
    -   python-setuptools
    -   git
-   Other Packages:
    -   Python Pip
