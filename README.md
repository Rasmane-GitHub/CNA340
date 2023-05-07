# Project Title

This file calculates available IP's based on a given subnet.

To perform the calculation, I used this formula:
((256 - octet_one) * (256 - octet_two) * (256 - octet_three) * (256 - octet_four))

## Getting Started

These instructions will help you calculate available IPs based on a given subnet mask.

### Prerequisites

This script requires the latest Python version to run. The commands below will install Python.

```
sudo apt-get install python3
```

## Running
Once installed you can run the program with the following command

```
python available_ip.py
```

## Thanks
Provide thank yous and attributions here. If someone helped you, you looked at another repository, or another article, provide it here.
