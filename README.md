## Overview
Ansible configuration for bootstrapping a RaspberryPi Kubernetes cluster.

## Notable Parts
- `k3s` instead of full blown Kubernetes because it's much more lightweight
- Mounts USB drives instead of HDD. Yes, they are way less durable...But they are also super cheap...
