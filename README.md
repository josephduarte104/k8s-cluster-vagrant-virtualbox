# Create a Kubernetes luster using vagrant

## Introduction

I’ve just started learning Kubernetes and wanted to test it on a cluster of VMs on my System 76 Lemur Pro. In this post, I’ll explain how I managed to get the cluster running by using Vagrant to create the VMs, and Ansible to automate the Kubernetes installation.

## Before you begin

Before you start this tutorial, you’ll need to download and install VirtualBox, Vagrant and Ansible on your local machine. The following steps have been tested on a Pop_OS! Ubunto with the following versions:

- VirtualBox 6.0.14 (Download VirtualBox)
- Vagrant 2.2.6 (Download Vagrant)
- Ansible 2.9.6

## Create CLuster
 
$ vagrant up

## login to master

$ vagrant ssh master


