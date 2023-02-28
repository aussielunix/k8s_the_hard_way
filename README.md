## Setup

k8s version: **1.23.5**

container runtime: [containerd](https://containerd.io/)

service discovery: [coredns](https://coredns.io/)

network provider: [canal](https://projectcalico.docs.tigera.io/getting-started/kubernetes/flannel/flannel)

## Setup

Create a new Python venv and install Python and Ansible deps

```bash
python -m venv lkthw-venv
source lkthw-venv/bin/activate
pip install -r requirements.txt
ansible-galaxy install -r .requirements.yml
```

## Old Instructions here:

[https://pythops.com/post/kubernetes-the-hard-way-part-1](https://pythops.com/post/kubernetes-the-hard-way-part-1)

[https://pythops.com/post/kubernetes-the-hard-way-part-2](https://pythops.com/post/kubernetes-the-hard-way-part-2)

## Author
Badr BADRI @pythops

## License
MIT
