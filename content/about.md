---
title: "About"
date: 2023-01-07T07:19:15+01:00
draft: false
comments: false
images:
tags: personal
categories: projects
---

# Who is Dominic Cardellino?

I grew up in Leinfelden-Echterdingen, a city nearby Stuttgart, Germany.
After school, I started my apprenticeship as an IT specialist (in german: Fachinformatiker). After this I gained some experience in System Administration at a german car manufacturer.

But this did not satisfy my needs of working in IT. So I changed my employer and got my hands dirty as a Windows Server Administrator.

Administering a virtualization environment with about 40 physical servers and more than 500 virtual servers based on VMWare was one part of my job. Managing the Active Directory, Exchange Server, SharePoint and monitoring all those things was the other part.

At some time there was a change in it management. The new Head of IT brought some kind of the "DevOps Mindset" to the really old fashioned it department. I started to have interest in automating the provisioning of infrastructure with Terraform. Deploying and configuring software with ansible.

So we started to automating all the things we did prior to this manually by hand.
After having established Terraform and Ansible in the it department, there was the next big thing - Kubernetes.

As other it departments started providing their software as containers we needed something to orchestrate those.

This was the point where my Kubernetes journey started.

I started to dive in Kubernetes with "the hard way" ;). But then I discovered tools like `kubeadm` and some time later I started using Rancher. 

I wrote terraform modules to deploy kubernetes clusters via Rancher. After some time I had multiple clusters running on different cloud providers (AWS, GKE, VMWare vSphere).