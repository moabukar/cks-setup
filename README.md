# CKS Cluster Setup

This repository contains a Vagrantfile and bash scripts to create a K8s Cluster for the CKS exam practice with 1 master node and 1 worker node. 

The modifications are specific to setting up the cluster using Vagrant and might be specific to my development setup on a Mac OSX laptop. Using a bridge network.

Additionally, I've added a step in scripts/install_master.sh to output the token join command to a file so that it can be run automatically during the installation of the worker node.

- Start the cluster using >> `vagrant up`
- Refresh the cluster using >> `vagrant halt`
- Destroy the clusters using >> `vagrant destroy -f`


You can start the cluster using `vagrant up` and refresh the cluster using vagrant halt && vagrant destroy -f && vagrant up
