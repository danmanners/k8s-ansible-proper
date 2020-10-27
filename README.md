# Kubernetes - The Proper Deployment

Deploy Kubernetes the (subjectively) **correct** way!

## Systems

This repository assumes **ten** systems exist, each of which is running Ubuntu 18.04:

- One (1x) System for HAProxy
- Two (2x) Kubernetes Control-Plane Nodes
- Three (3x) ETCD Nodes
- Four (4x) Kubernetes Worker Nodes

This Ansible project will go through and provision each of them appropriately and accordingly.

## References

- [Kubernetes Docs - Reference for Installing and setting up Kubernetes with Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/#step-2-create-an-ansible-playbook-for-kubernetes-master)
- [Rancher's K3s Ansible Repo](https://github.com/rancher/k3s-ansible)
- [Kublr - On-Prem Multi-Master](https://docs.kublr.com/articles/onprem-multimaster/#on-premises-install-haproxy-as-a-load-balancer-and-configure-it-to-work-with-kubernetes-api-server)
- [Digital Ocean - Setting up a secure ETCD Cluster](https://www.digitalocean.com/community/tutorials/how-to-set-up-and-secure-an-etcd-cluster-with-ansible-on-ubuntu-18-04)
