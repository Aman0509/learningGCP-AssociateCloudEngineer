# GCP - Associate Cloud Engineer

## Contents

- [GCP ACE - Getting Started](#gcp-ace---getting-started)

    - [Introduction to Cloud and GCP - Google Cloud Platform](#introduction-to-cloud-and-gcp---google-cloud-platform)

- [Google Cloud Regions and Zones](#google-cloud-regions-and-zones)

    - [Need for Regions and Zones](#need-for-regions-and-zones)

    - [Understanding Regions and Zones in GCP](#understanding-regions-and-zones-in-gcp)

- [Google Compute Engine for Associate Cloud Engineer](#google-compute-engine-for-associate-cloud-engineer)

    - [Getting started with Google Compute Engine - GCE](#getting-started-with-google-compute-engine---gce)

    - [Understanding Machine Types and Images in Google Compute Engine](#understanding-machine-types-and-images-in-google-compute-engine)

    - [Installing HTTP Webserver on GCE VM](#installing-http-webserver-on-gce-vm)

    - [Understanding Internal and External IP addresses](#understanding-internal-and-external-ip-addresses)

    - [Playing with Static IP Addresses](#playing-with-static-ip-addresses)

    - [Simplifying the Web Server setup with Compute Engine Startup Script](#simplifying-the-web-server-setup-with-compute-engine-startup-script)

    - [Simplifying VM creation with Instance Templates](#simplifying-vm-creation-with-instance-templates)

    - [Reducing Launch Time with Custom Images](#reducing-launch-time-with-custom-images)

- [Google Compute - Optimizing Costs and Performance in GCP](#google-compute---optimizing-costs-and-performance-in-gcp)

    - [Understanding Sustained Use Discounts in GCP](#understanding-sustained-use-discounts-in-gcp)

    - [Understanding Committed Use Discounts in GCP](#understanding-committed-use-discounts-in-gcp)

    - [Saving Costs with Preemptible VMs](#saving-costs-with-preemptible-vms)

    - [Quick Update about Spot VMs](#quick-update-about-spot-vms)

    - [Understanding Billing for Google Compute Engine VMs](#understanding-billing-for-google-compute-engine-vms)

    - [Achieving High Availability with Live Migration and Automatic Restart](#achieving-high-availability-with-live-migration-and-automatic-restart)

    - [Understanding Custom Machine Types](#understanding-custom-machine-types)

    - [Exploring GPUs in Google Compute Engine](#exploring-gpus-in-google-compute-engine)

    - [Quick Review - Virtual Machines in Google Cloud Platform](#quick-review---virtual-machines-in-google-cloud-platform)

    - [Best Practices - Virtual Machines in Google Cloud Platform](#best-practices---virtual-machines-in-google-cloud-platform)

    - [Scenarios - Virtual Machines in Google Cloud Platform](#scenarios---virtual-machines-in-google-cloud-platform)

    - [Quick Review - Google Compute Engine](#quick-review---google-compute-engine)

- [GCloud for Associate Cloud Engineer](#gcloud-for-associate-cloud-engineer)

    - [Getting Started with GCloud](#getting-started-with-gcloud)

    - [Playing with GCloud Config Set](#playing-with-gcloud-config-set)

    - [Managing Multiple Configurations in GCloud](#managing-multiple-configurations-in-gcloud)

    - [Understanding Command Structure in GCloud to play with Services](#understanding-command-structure-in-gcloud-to-play-with-services)

    - [Playing with GCloud Compute Instance Create](#playing-with-gcloud-compute-instance-create)

    - [Setting Default Region and Zone for Compute Engine](#setting-default-region-and-zone-for-compute-engine)

    - [Exploring GCloud Commands - list and describe](#exploring-gcloud-commands---list-and-describe)

    - [Playing with Compute Instances in GCloud](#playing-with-compute-instances-in-gcloud)

    - [Playing with Instance Templates in GCloud](#playing-with-instance-templates-in-gcloud)

- [Getting Started with Instance Groups](#getting-started-with-instance-groups)

    - [Creating Managed Instance Groups (MIG)](#creating-managed-instance-groups-mig)

    - [Updating a MIG - Rolling Update and Restart](#updating-a-mig---rolling-update-and-restart)

    - [Scenarios - Instance Groups](#scenarios---instance-groups)

    - [Using GCloud to play with MIG](#using-gcloud-to-play-with-mig)

    - [GCloud and MIG - Making Updates](#gcloud-and-mig---making-updates)

    - [GCloud and MIG - Managing Templates Updates](#gcloud-and-mig---managing-templates-updates)

- [Load Balancing in GCP](#load-balancing-in-gcp)

    - [Getting Started with Cloud Load Balancing](#getting-started-with-cloud-load-balancing)

    - [Understanding HTTP, HTTPS, UDP and TCP Protocols](#understanding-http-https-udp-and-tcp-protocols)

    - [Creating a Load Balancer in GCP](#creating-a-load-balancer-in-gcp)

    - [Understanding Cloud Load Balancing Terminology in GCP](#understanding-cloud-load-balancing-terminology-in-gcp)

    - [Choosing a Load Balancer in GCP](#choosing-a-load-balancer-in-gcp)

    - [Explore Features of Load Balancers](#explore-features-of-load-balancers)

    - [Scenarios - Cloud Load Balancing](#scenarios---cloud-load-balancing)

- [Managed Services in Google Cloud Platform](#managed-services-in-google-cloud-platform)

    - [What are Managed Services?](#what-are-managed-services)

    - [Understanding IAAS and PAAS](#understanding-iaas-and-paas)

    - [Understanding Evolution to Containers and Containers Orchestration](#understanding-evolution-to-containers-and-containers-orchestration)

    - [Understanding Serverless](#understanding-serverless)

    - [Exploring Google Cloud Platform GCP Compute Services](#exploring-google-cloud-platform-gcp-compute-services)

- [Getting Started with Google Cloud Functions](#getting-started-with-google-cloud-functions)

    - [Cloud Functions - Important Concepts](#cloud-functions---important-concepts)

    - [Demo - Creating Cloud Functions](#demo---creating-cloud-functions)

- [Getting Started with Google Cloud Run](#getting-started-with-google-cloud-run)

- [Exploring Google Cloud Functions Gen 2](#exploring-google-cloud-functions-gen-2)

    - [Exploring Cloud Functions - Scaling and Concurrency](#exploring-cloud-functions---scaling-and-concurrency)

    - [Quick Overview of deploying Cloud Functions with GCloud](#quick-overview-of-deploying-cloud-functions-with-gcloud)

- [Encryption in Google Cloud with Cloud KMS](#encryption-in-google-cloud-with-cloud-kms)

    - [Understanding Data States](#understanding-data-states)

    - [Understanding Encryption - Symmetric and Asymmetric](#understanding-encryption---symmetric-and-asymmetric)

    - [Getting Started with Cloud KMS](#getting-started-with-cloud-kms)

- [Block and File Storage in GCP](#block-and-file-storage-in-gcp)

    - [Exploring Block and File Storage in GCP](#exploring-block-and-file-storage-in-gcp)

    - [Exploring Block Storage in GCP - Local SSDs](#exploring-block-storage-in-gcp---local-ssds)

    - [Exploring Block Storage in GCP - Persistent Disks](#exploring-block-storage-in-gcp---persistent-disks)

    - [Comparing Persistent Disks vs Local SSDs](#comparing-persistent-disks-vs-local-ssds)

    - [Exploring Persistent Disks Types](#exploring-persistent-disks-types)

    - [Taking Snapshots for Persistent Disks](#taking-snapshots-for-persistent-disks)

    - [Playing with Persistent Disks and Snapshots](#playing-with-persistent-disks-and-snapshots)

    - [Playing with machine images](#playing-with-machine-images)

    - [Comparing Snapshots vs Images vs Machine Images](#comparing-snapshots-vs-images-vs-machine-images)

    - [Playing with Disks - GCloud](#playing-with-disks---gcloud)

    - [Playing with Images - GCloud](#playing-with-images---gcloud)

    - [Scenarios - Persistent Disks](#scenarios---persistent-disks)

    - [Exploring File Storage with FileStore](#exploring-file-storage-with-filestore)

    - [Exploring Global, Regional and Zonal Resources](#exploring-global-regional-and-zonal-resources)

    - [Scenarios - Block and File Storage](#scenarios---block-and-file-storage)

- [Object Storage in GCP - Cloud Storage](#object-storage-in-gcp---cloud-storage)

    - [Playing with Object Storage in GCP - Cloud Storage](#playing-with-object-storage-in-gcp---cloud-storage)

    - [Exploring Cloud Storage in GCP](#exploring-cloud-storage-in-gcp)

    - [Understanding Cloud Storage - Objects and Buckets](#understanding-cloud-storage---objects-and-buckets)

    - [Understanding Cloud Storage - Storage Classes](#understanding-cloud-storage---storage-classes)

    - [Understanding Cloud Storage - Uploading and Downloading Options](#understanding-cloud-storage---uploading-and-downloading-options)

    - [Understanding Cloud Storage - Versioning](#understanding-cloud-storage---versioning)

    - [Understanding Cloud Storage - Lifecycle Management](#understanding-cloud-storage---lifecycle-management)

    - [Understanding Cloud Storage - Encryption with KMS](#understanding-cloud-storage---encryption-with-kms)

    - [Scenarios - Cloud Storage](#scenarios---cloud-storage)

    - [Playing with gsutil - Cloud Storage from Command Line](#playing-with-gsutil---cloud-storage-from-command-line)

- [Authentication & Authorization in Google Cloud with Cloud IAM](#authentication--authorization-in-google-could-with-cloud-iam)

    - [Introduction](#introduction)

    - [Exploring Cloud IAM Roles](#exploring-cloud-iam-roles)

    - [Playing with IAM Roles - Predefined, Basic and Custom Roles](#playing-with-iam-roles---predefined-basic-and-custom-roles)

    - [Exploring Cloud IAM - Members, Role and Policy](#exploring-cloud-iam---members-role-and-policy)

    - [Demo - Playing with IAM (DIY)](#demo---playing-with-iam-diy)

    - [Getting started with Service Accounts](#getting-started-with-service-accounts)

    - [Demo - Playing with Service Accounts](#demo---playing-with-service-accounts)

    - [Exploring Service Account Use Cases](#exploring-service-account-use-cases)

    - [Scenarios - Service Accounts](#scenarios---service-accounts)

    - [ACL(Access Control Lists)](#aclaccess-control-lists)

    - [Signed URLs - Part of Cloud Storage](#signed-urls---part-of-cloud-storage)

    - [Exposing a Public Website using Cloud Storage](#exposing-a-public-website-using-cloud-storage)

- [Choosing Database in GCP](#choosing-database-in-gcp)

    - [Understanding Database Fundamentals - Snapshot, Standby etc](#understanding-database-fundamentals---snapshot-standby-etc)

    - [Understanding Database Fundamentals - Availability and Durability](#understanding-database-fundamentals---availability-and-durability)

    - [Understanding Database Fundamentals - RTO and RPO](#understanding-database-fundamentals---rto-and-rpo)

    - [Understanding Database Fundamentals - Read Replicas](#understanding-database-fundamentals---read-replicas)

    - [Understanding Database Fundamentals - Data Consistency](#understanding-database-fundamentals---data-consistency)

    - [Understanding Database Fundamentals - Choosing Databases](#understanding-database-fundamentals---choosing-databases)

    - [OLTP Relational Databases in Google Cloud - Cloud SQL and Cloud Spanner](#oltp-relational-databases-in-google-cloud---cloud-sql-and-cloud-spanner)

    - [OLAP Relational Databases in Google Cloud - BigQuery](#olap-relational-databases-in-google-cloud---bigquery)

    - [NoSQL Databases in Google Cloud - Firestone, Datastore and BigTable](#nosql-databases-in-google-cloud---firestone-datastore-and-bigtable)

    - [In Memory Database in Google Cloud - Memorystore](#in-memory-database-in-google-cloud---memorystore)

    - [Databases in Google Cloud Platform - A Quick Review](#databases-in-google-cloud-platform---a-quick-review)

    - [Databases in Google Cloud Platform - Scenarios](#databases-in-google-cloud-platform---scenarios)

- [Exploring Databases in Google Cloud Platform](#exploring-databases-in-google-cloud-platform)

    - [Getting Started with Cloud SQL](#getting-started-with-cloud-sql)

    - [Demo - Playing with CloudSQL](#demo---playing-with-cloudsql)

    - [Understanding CloudSQL Features](#understanding-cloudsql-features)

    - [Getting Started with Cloud Spanner](#getting-started-with-cloud-spanner)

    - [Demo - Playing with Cloud Spanner](#demo---playing-with-cloud-spanner)

    - [Getting Started with Cloud Datastore and Cloud Firestore](#getting-started-with-cloud-datastore-and-cloud-firestore)

    - [Demo - Playing with Firestore](#demo---playing-with-firestore)

    - [Getting Started with Cloud BigTable](#getting-started-with-cloud-bigtable)

    - [Getting Started with Memorystore](#getting-started-with-memorystore)

    - [Demo - Playing with Memorystore](#demo---playing-with-memorystore)

    - [Getting Started with BigQuery](#getting-started-with-bigquery)

    - [Playing with Cloud SQL, BigQuery and Big Table from Command Line](#playing-with-cloud-sql-bigquery-and-big-table-from-command-line)

    - [Importing and Exporting Relational Databases](#importing-and-exporting-relational-databases)

    - [Importing and Exporting NoSQL Databases](#importing-and-exporting-nosql-databases)

    - [Databases in Google Cloud Platform - Summary](#databases-in-google-cloud-platform---summary)

- [Asynchronous Communication in Google Cloud with Cloud Pub Sub](#asynchronous-communication-in-google-cloud-with-cloud-pub-sub)

    - [Understanding the need for Asynchronous Communication](#understanding-the-need-for-asynchronous-communication)

    - [Getting Started with Cloud Pub Sub](#getting-started-with-cloud-pub-sub)

    - [Exploring Cloud Pub Sub - Publishing and Consuming a Message](#exploring-cloud-pub-sub---publishing-and-consuming-a-message)

    - [Demo - Playing with Pub/Sub](#demo---playing-with-pubsub)

- [Private Networks in Google Cloud - Cloud VPC](#private-networks-in-google-cloud---cloud-vpc)

    - [Understanding the need for Google Cloud VPC - Virtual Private Cloud](#understanding-the-need-for-google-cloud-vpc---virtual-private-cloud)

    - [Understanding the need for VPC subnets](#understanding-the-need-for-vpc-subnets)

    - [Creating VPCs and Subnets in GCP](#creating-vpcs-and-subnets-in-gcp)

    - [Understanding Firewall Rules in GCP](#understanding-firewall-rules-in-gcp)

    - [Getting Started with Shared VPC](#getting-started-with-shared-vpc)

    - [Getting Started with VPC Peering](#getting-started-with-vpc-peering)

    - [Implementing Hybrid Cloud with Cloud VPN and Cloud Interconnect](#implementing-hybrid-cloud-with-cloud-vpn-and-cloud-interconnect)

- [Operations in Google Cloud Platform](#operations-in-google-cloud-platform)

    - [Getting Started with Google Cloud Monitoring](#getting-started-with-google-cloud-monitoring)

    - [Getting Started with Google Cloud Logging](#getting-started-with-google-cloud-logging)

    - [Exploring Google Cloud Logging - Audit Logs](#exploring-google-cloud-logging---audit-logs)

    - [Exploring Google Cloud Logging - Routing Logs and Exports](#exploring-google-cloud-logging---routing-logs-and-exports)

    - [Creating a Cloud Storage Bucket and Cloud Function](#creating-a-cloud-storage-bucket-and-cloud-function)

    - [Getting Started with Google Cloud Trace](#getting-started-with-google-cloud-trace)

    - [Getting Started with Google Cloud Debugger](#getting-started-with-google-cloud-debugger)

    - [Cloud Profiler and Error Reporting](#cloud-profiler-and-error-reporting)

    - [Scenarios - Operations in GCP](#scenarios---operations-in-gcp)

- [Organizations and IAM - Organizing Google Cloud Resources](#organizations-and-iam---organizing-google-cloud-resources)

    - [Organizing Google Cloud Resources - Projects, Folders and Organization](#organizing-google-cloud-resources---projects-folders-and-organization)

    - [Exploring Billing Accounts](#exploring-billing-accounts)

    - [Understanding IAM Best Practice](#understanding-iam-best-practice)

    - [Understanding User Identity Management in GCP](#understanding-user-identity-management-in-gcp)

    - [Exploring IAM Members and Identities](#exploring-iam-members-and-identities)

    - [Understanding Organization Policy Service](#understanding-organization-policy-service)

    - [Exploring IAM policy at multiple levels - Resource Hierarchy](#exploring-iam-policy-at-multiple-levels---resource-hierarchy)

    - [Exploring IAM Predefined Roles - Organization, Billing and Project](#exploring-iam-predefined-roles---organization-billing-and-project)

    - [Exploring IAM Predefined Roles - Google Compute Engine](#exploring-iam-predefined-roles---google-compute-engine)

    - [Exploring IAM Predefined Roles - Google App Engine](#exploring-iam-predefined-roles---google-app-engine)

    - [Exploring IAM Predefined Roles - Scenarios](#exploring-iam-predefined-roles---scenarios)

    - [Exploring IAM Predefined Roles - Google Kubernetes Engine](#exploring-iam-predefined-roles---google-kubernetes-engine)

    - [Exploring IAM Predefined Roles - Google Cloud Storage](#exploring-iam-predefined-roles---google-cloud-storage)

    - [Exploring IAM Predefined Roles - Google Cloud BigQuery](#exploring-iam-predefined-roles---google-cloud-bigquery)

    - [Exploring IAM Predefined Roles - Logging Service Accounts](#exploring-iam-predefined-roles---logging-service-accounts)

    - [Other Important IAM Roles](#other-important-iam-roles)

    - [SSHing into Linux VMs](#sshing-into-linux-vms)

    - [Exploring IAM Scenarios](#exploring-iam-scenarios)

- [Exploring Google Cloud Platform - GCP - Pricing Calculator](#exploring-google-cloud-platform---gcp---pricing-calculator)

- [Google Cloud Platform - Other Important Services](#google-cloud-platform---other-important-services)

    - [Getting Started with Cloud Deployment Manager](#getting-started-with-cloud-deployment-manager)

    - [Understanding Cloud Deployment Manager](#understanding-cloud-deployment-manager)

    - [Getting Started with Cloud Marketplace](#getting-started-with-cloud-marketplace)

    - [Getting Started with Cloud DNS](#getting-started-with-cloud-dns)

    - [Getting Started with Cloud Dataflow](#getting-started-with-cloud-dataflow)

    - [Getting Started with Cloud Dataproc](#getting-started-with-cloud-dataproc)

- [References](#references)

## GCP ACE - Getting Started

### Introduction to Cloud and GCP - Google Cloud Platform

![in28minutes slide image](other/images/cloud_ace_getting_started/1_cloud_ace_getting_started.png)

![in28minutes slide image](other/images/cloud_ace_getting_started/2_cloud_ace_getting_started.png)

![in28minutes slide image](other/images/cloud_ace_getting_started/3_cloud_ace_getting_started.png)

![in28minutes slide image](other/images/cloud_ace_getting_started/4_cloud_ace_getting_started.png)

![in28minutes slide image](other/images/cloud_ace_getting_started/5_cloud_ace_getting_started.png)

![in28minutes slide image](other/images/cloud_ace_getting_started/6_cloud_ace_getting_started.png)

## Google Cloud Regions and Zones

### Need for Regions and Zones

![in28minutes slide image](other/images/cloud_regions_and_zones/1_cloud_regions_and_zones.png)

![in28minutes slide image](other/images/cloud_regions_and_zones/2_cloud_regions_and_zones.png)

![in28minutes slide image](other/images/cloud_regions_and_zones/3_cloud_regions_and_zones.png)

### Understanding Regions and Zones in GCP

![in28minutes slide image](other/images/cloud_regions_and_zones/4_cloud_regions_and_zones.png)

![in28minutes slide image](other/images/cloud_regions_and_zones/5_cloud_regions_and_zones.png)

![in28minutes slide image](other/images/cloud_regions_and_zones/6_cloud_regions_and_zones.png)

## Google Compute Engine for Associate Cloud Engineer

### Getting started with Google Compute Engine - GCE

![in28minutes slide image](other/images/cloud_compute_engine/1_cloud_compute_engine.png)

![in28minutes slide image](other/images/cloud_compute_engine/2_cloud_compute_engine.png)

![in28minutes slide image](other/images/cloud_compute_engine/3_cloud_compute_engine.png)

- Go to search bar > type 'compute engine' and hit enter > create

    ![in28minutes demo image](other/images/cloud_compute_engine/4_cloud_compute_engine.png)

- Provide configurations like, name, region, machine type, os details etc and then click on create.

Readings:

- [Creating a Virtual Machine Instance with Google Cloud](https://www.waferwire.com/blog/creating-a-virtual-machine-instance-with-google-cloud/)

- [Create a Google Compute Engine stack](https://www.koding.com/docs/creating-a-gce-stack)

### Understanding Machine Types and Images in Google Compute Engine

![in28minutes slide image](other/images/cloud_compute_engine/5_cloud_compute_engine.png)

![in28minutes slide image](other/images/cloud_compute_engine/6_cloud_compute_engine.png)

![in28minutes slide image](other/images/cloud_compute_engine/7_cloud_compute_engine.png)

### Installing HTTP Webserver on GCE VM

- Once VM is created, install Apache in it and inside the index page, let's just keep the VM's hostname and IP address.

    ![in28minutes slide image](other/images/cloud_compute_engine/8_cloud_compute_engine.png)

- To launch the index page hosted on VM, use the **External IP**. Make sure you have allow the HTTP/HTTPS traffic on this VM.

    ![in28minutes demo image](other/images/cloud_compute_engine/9_cloud_compute_engine.png)

    ![in28minutes demo image](other/images/cloud_compute_engine/10_cloud_compute_engine.png)

### Understanding Internal and External IP addresses

![in28minutes slide image](other/images/cloud_compute_engine/11_cloud_compute_engine.png)

### Playing with Static IP Addresses

![in28minutes slide image](other/images/cloud_compute_engine/12_cloud_compute_engine.png)

- Go to Search bar > type **External IP Addresses** > list of all external IP addresses can be found here which are assigned to VMs

    ![in28minutes demo image](other/images/cloud_compute_engine/13_cloud_compute_engine.png)

- Now to reserver an IP or create a static IP, click on **Reserve Static Address** and provide the configurations.

    ![in28minutes demo image](other/images/cloud_compute_engine/14_cloud_compute_engine.png)

    ![in28minutes demo image](other/images/cloud_compute_engine/15_cloud_compute_engine.png)

- Once static IP is created, it needs to be assigned to the VM. For that, click on **change** and select the VM.

    ![in28minutes demo image](other/images/cloud_compute_engine/16_cloud_compute_engine.png)

![in28minutes slide image](other/images/cloud_compute_engine/17_cloud_compute_engine.png)

### Simplifying the Web Server setup with Compute Engine Startup Script

![in28minutes slide image](other/images/cloud_compute_engine/18_cloud_compute_engine.png)

![in28minutes slide image](other/images/cloud_compute_engine/19_cloud_compute_engine.png)

We will configure our startup script during VM creation. For that, while creating VM and configuring options, go to **Management** > under **Automation**, you will find **Startup script** text area. Update your script there and create instance.

![in28minutes demo image](other/images/cloud_compute_engine/20_cloud_compute_engine.png)

To test it, click on external IP and verify everything's working as expected.

### Simplifying VM creation with Instance Templates

![in28minutes slide image](other/images/cloud_compute_engine/21_cloud_compute_engine.png)

![in28minutes demo image](other/images/cloud_compute_engine/22_cloud_compute_engine.png)

![in28minutes demo image](other/images/cloud_compute_engine/23_cloud_compute_engine.png)

![in28minutes demo image](other/images/cloud_compute_engine/24_cloud_compute_engine.png)

Click on create and new instance template will be created. Based on it, now, VMs can be created.

![in28minutes demo image](other/images/cloud_compute_engine/25_cloud_compute_engine.png)

### Reducing Launch Time with Custom Images

![in28minutes slide image](other/images/cloud_compute_engine/26_cloud_compute_engine.png)

To create image from a disk, ensure VM instance attached with that disk should be in stopped state.

![in28minutes demo image](other/images/cloud_compute_engine/27_cloud_compute_engine.png)

Provide all required configurations and click on create. Once created, you can find it under **Images** tab.

![in28minutes demo image](other/images/cloud_compute_engine/28_cloud_compute_engine.png)

Now, you can create an instance template and use this custom image under boot disk section and create VM instances based on this template.

## Google Compute - Optimizing Costs and Performance in GCP

### Understanding Sustained Use Discounts in GCP

![in28minutes slide image](other/images/cloud_optimizing_costs/1_cloud_optimizing_costs.png)

### Understanding Committed Use Discounts in GCP

![in28minutes slide image](other/images/cloud_optimizing_costs/2_cloud_optimizing_costs.png)

![in28minutes demo image](other/images/cloud_optimizing_costs/3_cloud_optimizing_costs.png)

![in28minutes demo image](other/images/cloud_optimizing_costs/4_cloud_optimizing_costs.png)

### Saving Costs with Preemptible VMs

![in28minutes slide image](other/images/cloud_optimizing_costs/5_cloud_optimizing_costs.png)

Proceed with the VM creation and select under **Management, security, disks, networking, sole tenancy**

![in28minutes demo image](other/images/cloud_optimizing_costs/6_cloud_optimizing_costs.png)

![in28minutes demo image](other/images/cloud_optimizing_costs/7_cloud_optimizing_costs.png)

### Quick Update about Spot VMs

![in28minutes slide image](other/images/cloud_optimizing_costs/8_cloud_optimizing_costs.png)

### Understanding Billing for Google Compute Engine VMs

![in28minutes slide image](other/images/cloud_optimizing_costs/9_cloud_optimizing_costs.png)

![in28minutes demo image](other/images/cloud_optimizing_costs/10_cloud_optimizing_costs.png)

Click on 'Create Budget' and configure as per your requirements.

### Achieving High Availability with Live Migration and Automatic Restart

![in28minutes slide image](other/images/cloud_optimizing_costs/11_cloud_optimizing_costs.png)

![in28minutes demo image](other/images/cloud_optimizing_costs/12_cloud_optimizing_costs.png)

### Understanding Custom Machine Types

![in28minutes slide image](other/images/cloud_optimizing_costs/13_cloud_optimizing_costs.png)

![in28minutes demo image](other/images/cloud_optimizing_costs/14_cloud_optimizing_costs.png)

### Exploring GPUs in Google Compute Engine

![in28minutes slide image](other/images/cloud_optimizing_costs/15_cloud_optimizing_costs.png)

There are 2 ways of creating GPU machines:

**1st Way**

![in28minutes demo image](other/images/cloud_optimizing_costs/16_cloud_optimizing_costs.png)

**2nd Way**

Select machine type and then add GPU to it.

![in28minutes demo image](other/images/cloud_optimizing_costs/17_cloud_optimizing_costs.png)

### Quick Review - Virtual Machines in Google Cloud Platform

![in28minutes slide image](other/images/cloud_optimizing_costs/18_cloud_optimizing_costs.png)

### Best Practices - Virtual Machines in Google Cloud Platform

![in28minutes slide image](other/images/cloud_optimizing_costs/19_cloud_optimizing_costs.png)

### Scenarios - Virtual Machines in Google Cloud Platform

![in28minutes slide image](other/images/cloud_optimizing_costs/20_cloud_optimizing_costs.png)

### Quick Review - Google Compute Engine

![in28minutes slide image](other/images/cloud_optimizing_costs/21_cloud_optimizing_costs.png)

![in28minutes slide image](other/images/cloud_optimizing_costs/22_cloud_optimizing_costs.png)

## GCloud for Associate Cloud Engineer

### Getting Started with GCloud

![in28minutes slide image](other/images/cloud_gcloud/1_cloud_gcloud.png)

![in28minutes slide image](other/images/cloud_gcloud/2_cloud_gcloud.png)

### Playing with GCloud Config Set

![in28minutes slide image](other/images/cloud_gcloud/3_cloud_gcloud.png)

### Managing Multiple Configurations in GCloud

![in28minutes slide image](other/images/cloud_gcloud/4_cloud_gcloud.png)

### Understanding Command Structure in GCloud to play with Services

![in28minutes slide image](other/images/cloud_gcloud/5_cloud_gcloud.png)

### Playing with GCloud Compute Instance Create

![in28minutes slide image](other/images/cloud_gcloud/6_cloud_gcloud.png)

### Setting Default Region and Zone for Compute Engine

![in28minutes slide image](other/images/cloud_gcloud/7_cloud_gcloud.png)

### Exploring GCloud Commands - list and describe

![in28minutes slide image](other/images/cloud_gcloud/8_cloud_gcloud.png)

### Playing with Compute Instances in GCloud

![in28minutes slide image](other/images/cloud_gcloud/9_cloud_gcloud.png)

### Playing with Instance Templates in GCloud

![in28minutes slide image](other/images/cloud_gcloud/10_cloud_gcloud.png)

## Getting Started with Instance Groups

![in28minutes slide image](other/images/cloud_managed_instance_group/1_cloud_managed_instance_group.png)

![in28minutes slide image](other/images/cloud_managed_instance_group/2_cloud_managed_instance_group.png)

### Creating Managed Instance Groups (MIG)

![in28minutes slide image](other/images/cloud_managed_instance_group/3_cloud_managed_instance_group.png)

![in28minutes demo image](other/images/cloud_managed_instance_group/4_cloud_managed_instance_group.png)

Provide configurations as per your requirements and click on create.

![in28minutes demo image](other/images/cloud_managed_instance_group/5_cloud_managed_instance_group.png)

### Updating a MIG - Rolling Update and Restart

![in28minutes slide image](other/images/cloud_managed_instance_group/6_cloud_managed_instance_group.png)

**Rolling Update**

To configure rolling update, go to instance groups > update VMs

![in28minutes demo image](other/images/cloud_managed_instance_group/7_cloud_managed_instance_group.png)

In this scenario, let's say you want this MIG to run on different Instance template. In summary, you want to update the instance template.

![in28minutes demo image](other/images/cloud_managed_instance_group/8_cloud_managed_instance_group.png)

After that, select type update. With ***Automatic*** update type, you've few more configure options to select.

![in28minutes demo image](other/images/cloud_managed_instance_group/9_cloud_managed_instance_group.png)

![in28minutes demo image](other/images/cloud_managed_instance_group/10_cloud_managed_instance_group.png)

![in28minutes demo image](other/images/cloud_managed_instance_group/11_cloud_managed_instance_group.png)

**Rolling Restart**

![in28minutes demo image](other/images/cloud_managed_instance_group/12_cloud_managed_instance_group.png)

![in28minutes demo image](other/images/cloud_managed_instance_group/13_cloud_managed_instance_group.png)

### Scenarios - Instance Groups

![in28minutes slide image](other/images/cloud_managed_instance_group/14_cloud_managed_instance_group.png)

### Using GCloud to play with MIG

![in28minutes slide image](other/images/cloud_managed_instance_group/15_cloud_managed_instance_group.png)

### GCloud and MIG - Making Updates

![in28minutes slide image](other/images/cloud_managed_instance_group/16_cloud_managed_instance_group.png)

### GCloud and MIG - Managing Templates Updates

In the last section, we looked at a few ways to make updates to our managed instance group and it was concluded with setting of instance template. However, one thing that we did not discuss is when would the template be updated? Will it be updated immediately?

Note that the manage ***instance group configuration*** would be updated immediately, but would the instance be immediately updated to that template? Will there be any downtime while making the update to that specific template?

The answer to that is after updating the instance template you can configure how to do the update. How do you roll out the new template to the existing virtual machines?

There are multiple commands that you can make use of. You can make use of the *recreate-instances* and the *update-instances* that we have used earlier. Or there is another set of command which you can use called *rolling-action start-update*.

![in28minutes slide image](other/images/cloud_managed_instance_group/17_cloud_managed_instance_group.png)

When you're doing *recreate-instances*, you are doing everything manually. However, you can also automate the upgrade to the new version template in a more controlled fashion using *rolling-action start-update*.

![in28minutes slide image](other/images/cloud_managed_instance_group/18_cloud_managed_instance_group.png)

## Load Balancing in GCP

### Getting Started with Cloud Load Balancing

![in28minutes slide image](other/images/cloud_load_balancing/1_cloud_load_balancing.png)

### Understanding HTTP, HTTPS, UDP and TCP Protocols

![in28minutes slide image](other/images/cloud_load_balancing/2_cloud_load_balancing.png)

![in28minutes slide image](other/images/cloud_load_balancing/3_cloud_load_balancing.png)

![in28minutes slide image](other/images/cloud_load_balancing/4_cloud_load_balancing.png)

Readings:

- [OSI Model Layers and Protocols in Computer Network](https://www.guru99.com/layers-of-osi-model.html)

### Creating a Load Balancer in GCP

![in28minutes demo image](other/images/cloud_load_balancing/5_cloud_load_balancing.png)

Select type of load balancing as per your requirement.

![in28minutes demo image](other/images/cloud_load_balancing/6_cloud_load_balancing.png)

Let's create a HTTP(s) load balancer. For that, click on *Start Configuration* and provide configurations.

![in28minutes demo image](other/images/cloud_load_balancing/7_cloud_load_balancing.png)

Click on *Continue* and configure backend, host and path rules and frontend.

![in28minutes demo image](other/images/cloud_load_balancing/8_cloud_load_balancing.png)

### Understanding Cloud Load Balancing Terminology in GCP

![in28minutes slide image](other/images/cloud_load_balancing/9_cloud_load_balancing.png)

![in28minutes slide image](other/images/cloud_load_balancing/10_cloud_load_balancing.png)

Readings:

- [Cloud Load Balancing overview](https://cloud.google.com/load-balancing/docs/load-balancing-overview)

### Choosing a Load Balancer in GCP

![google cloud docs image](other/images/cloud_load_balancing/11_cloud_load_balancing.png)

Readings:

- [Choose a load balancer](https://cloud.google.com/load-balancing/docs/choosing-load-balancer)

### Explore Features of Load Balancers

![in28minutes slide image](other/images/cloud_load_balancing/12_cloud_load_balancing.png)

### Scenarios - Cloud Load Balancing

![in28minutes slide image](other/images/cloud_load_balancing/13_cloud_load_balancing.png)

## Managed Services in Google Cloud Platform

### What are Managed Services?

![in28minutes slide image](other/images/cloud_managed_services/1_cloud_managed_services.png)

### Understanding IAAS and PAAS

![in28minutes slide image](other/images/cloud_managed_services/2_cloud_managed_services.png)

![in28minutes slide image](other/images/cloud_managed_services/3_cloud_managed_services.png)

### Understanding Evolution to Containers and Containers Orchestration

![in28minutes slide image](other/images/cloud_managed_services/4_cloud_managed_services.png)

![in28minutes slide image](other/images/cloud_managed_services/5_cloud_managed_services.png)

![in28minutes slide image](other/images/cloud_managed_services/6_cloud_managed_services.png)

### Understanding Serverless

![in28minutes slide image](other/images/cloud_managed_services/7_cloud_managed_services.png)

![in28minutes slide image](other/images/cloud_managed_services/8_cloud_managed_services.png)

### Exploring Google Cloud Platform GCP Compute Services

![in28minutes slide image](other/images/cloud_managed_services/9_cloud_managed_services.png)

## Getting Started with Google Cloud Functions

![in28minutes slide image](other/images/cloud_functions/1_cloud_functions.png)

Readings:

- [What is Google Cloud Functions?](https://iromin.medium.com/google-cloud-functions-tutorial-what-is-google-cloud-functions-8796fa07fc7a)

### Cloud Functions - Important Concepts

![in28minutes slide image](other/images/cloud_functions/2_cloud_functions.png)

![in28minutes slide image](other/images/cloud_functions/3_cloud_functions.png)

### Demo - Creating Cloud Functions

- [Cloudera Docs](https://docs.cloudera.com/dataflow/cloud/google-cloud-functions/topics/cdf-create-google-cloud-function.html)

- [Codelabs](https://codelabs.developers.google.com/codelabs/cloud-starting-cloudfunctions#0)

## Getting Started with Google Cloud Run

![in28minutes slide image](other/images/cloud_run/1_cloud_run.png)

![Google Developers slide image](other/images/cloud_run/2_cloud_run.png)

![Google Developers slide image](other/images/cloud_run/3_cloud_run.png)

![Google Developers slide image](other/images/cloud_run/4_cloud_run.png)

![Google Developers slide image](other/images/cloud_run/5_cloud_run.png)

![in28minutes slide image](other/images/cloud_run/6_cloud_run.png)

Readings:

- [What is Cloud Run?](https://www.bmc.com/blogs/google-cloud-run/)

- [Cloud Run and serverless computing](https://developers.google.com/learn/pathways/cloud-run-serverless-computing)

## Exploring Google Cloud Functions Gen 2

![in28minutes slide image](other/images/cloud_functions/4_cloud_functions.png)

Readings:

- [2nd Generation Google Cloud Function](https://medium.com/geekculture/2nd-generation-google-cloud-function-a069a131e313)

- [Cloud Functions version comparison](https://cloud.google.com/functions/docs/concepts/version-comparison)

### Exploring Cloud Functions - Scaling and Concurrency

![in28minutes slide image](other/images/cloud_functions/5_cloud_functions.png)

### Quick Overview of deploying Cloud Functions with GCloud

![in28minutes slide image](other/images/cloud_functions/6_cloud_functions.png)

![in28minutes slide image](other/images/cloud_functions/7_cloud_functions.png)

## Encryption in Google Cloud with Cloud KMS

### Understanding Data States

![in28minutes slide image](other/images/cloud_kms/1_cloud_kms.png)

### Understanding Encryption - Symmetric and Asymmetric

![in28minutes slide image](other/images/cloud_kms/2_cloud_kms.png)

![in28minutes slide image](other/images/cloud_kms/3_cloud_kms.png)

![in28minutes slide image](other/images/cloud_kms/4_cloud_kms.png)

### Getting Started with Cloud KMS

![in28minutes slide image](other/images/cloud_kms/5_cloud_kms.png)

Readings:

- [Deep Dive Into Google Cloud Key Management Services](https://www.appviewx.com/blogs/deep-dive-into-google-cloud-key-management-services/)

## Block and File Storage in GCP

### Exploring Block and File Storage in GCP

![in28minutes slide image](other/images/cloud_block_and_file_storage/1_cloud_block_and_file_storage.png)

![in28minutes slide image](other/images/cloud_block_and_file_storage/2_cloud_block_and_file_storage.png)

![in28minutes slide image](other/images/cloud_block_and_file_storage/3_cloud_block_and_file_storage.png)

![in28minutes slide image](other/images/cloud_block_and_file_storage/4_cloud_block_and_file_storage.png)

Let's quickly see where you can actually look at these options.

So, when we create a virtual machine, that's when you can attach block storage devices with it. You can either attach persistent disks or local SSDs.

During creation of VM, if you go to the boot disk, you will see a persistent disk is attached from where your operating system is loaded and whenever we create a virtual machine, a boot disk is automatically attached with the virtual machine. So by default, a persistent disk called a boot disk is attached with your VM.

![in28minutes demo image](other/images/cloud_block_and_file_storage/5_cloud_block_and_file_storage.png)

If you'd want to have additional persistent disks attached, then go to Disks > Add New Disk

![in28minutes demo image](other/images/cloud_block_and_file_storage/6_cloud_block_and_file_storage.png)

> Remember, Local SSD is available with selected machine types

Readings:

- [Google Cloud Platform – Filestore](https://www.geeksforgeeks.org/google-cloud-platform-filestore/)

- [Setup Filestore (shared filesystem) on Google Cloud and mount on to Ubuntu systems](https://medium.com/geekculture/setup-filestore-shared-filesystem-on-google-cloud-and-mount-on-to-ubuntu-systems-157fb762b25c)

### Exploring Block Storage in GCP - Local SSDs

![in28minutes slide image](other/images/cloud_block_and_file_storage/7_cloud_block_and_file_storage.png)

![in28minutes slide image](other/images/cloud_block_and_file_storage/8_cloud_block_and_file_storage.png)

![in28minutes slide image](other/images/cloud_block_and_file_storage/9_cloud_block_and_file_storage.png)

### Exploring Block Storage in GCP - Persistent Disks

![in28minutes slide image](other/images/cloud_block_and_file_storage/10_cloud_block_and_file_storage.png)

### Comparing Persistent Disks vs Local SSDs

![in28minutes slide image](other/images/cloud_block_and_file_storage/11_cloud_block_and_file_storage.png)

### Exploring Persistent Disks Types

![in28minutes slide image](other/images/cloud_block_and_file_storage/12_cloud_block_and_file_storage.png)

### Taking Snapshots for Persistent Disks

![in28minutes slide image](other/images/cloud_block_and_file_storage/13_cloud_block_and_file_storage.png)

![in28minutes slide image](other/images/cloud_block_and_file_storage/14_cloud_block_and_file_storage.png)

Readings:

- [Google Cloud Compute Engine Snapshots](https://jayendrapatil.com/google-cloud-compute-engine-snapshots/)

### Playing with Persistent Disks and Snapshots

We know that boot disk of persistent disks. However, if you delete your VM, the boot disk will also get deleted. To avoid that you can configure like below:

*While creating the VM*

Go to Boot Disk > Change > Show Advanced Configuration > Deletion Rule > Keep Boot Disk

![in28minutes demo image](other/images/cloud_block_and_file_storage/15_cloud_block_and_file_storage.png)

*In a existing VM*

Go to you instance > Edit > Under Storage (Boot Disk) section > Deletion Rule > Keep Disk

![in28minutes demo image](other/images/cloud_block_and_file_storage/16_cloud_block_and_file_storage.png)

**Creating Snapshot**

![in28minutes demo image](other/images/cloud_block_and_file_storage/17_cloud_block_and_file_storage.png)

Once your snapshot is created, you can create an VM instance using it. But remember that snapshots must be created from a boot disk.

![in28minutes demo image](other/images/cloud_block_and_file_storage/18_cloud_block_and_file_storage.png)

You can also create a disk using snapshot.

![in28minutes demo image](other/images/cloud_block_and_file_storage/19_cloud_block_and_file_storage.png)

**Scheduling Snapshots**

Snapshot schedule is not really linked to a disk. It's a general schedule. Once created, you need to explicitly assigned it to a disk.

![in28minutes demo image](other/images/cloud_block_and_file_storage/20_cloud_block_and_file_storage.png)

![in28minutes demo image](other/images/cloud_block_and_file_storage/21_cloud_block_and_file_storage.png)

Assigning snapshot schedule to a disk.

![in28minutes demo image](other/images/cloud_block_and_file_storage/22_cloud_block_and_file_storage.png)

### Playing with machine images

![in28minutes slide image](other/images/cloud_block_and_file_storage/23_cloud_block_and_file_storage.png)

![in28minutes demo image](other/images/cloud_block_and_file_storage/24_cloud_block_and_file_storage.png)

After creating a machine image, instance can be created based on it.

![in28minutes demo image](other/images/cloud_block_and_file_storage/25_cloud_block_and_file_storage.png)

### Comparing Snapshots vs Images vs Machine Images

![in28minutes slide image](other/images/cloud_block_and_file_storage/26_cloud_block_and_file_storage.png)

### Playing with Disks - GCloud

![in28minutes slide image](other/images/cloud_block_and_file_storage/27_cloud_block_and_file_storage.png)

### Playing with Images - GCloud

![in28minutes slide image](other/images/cloud_block_and_file_storage/28_cloud_block_and_file_storage.png)

### Scenarios - Persistent Disks

![in28minutes slide image](other/images/cloud_block_and_file_storage/29_cloud_block_and_file_storage.png)

### Exploring File Storage with FileStore

![in28minutes slide image](other/images/cloud_block_and_file_storage/30_cloud_block_and_file_storage.png)

### Exploring Global, Regional and Zonal Resources

![in28minutes slide image](other/images/cloud_block_and_file_storage/31_cloud_block_and_file_storage.png)

### Scenarios - Block and File Storage

![in28minutes slide image](other/images/cloud_block_and_file_storage/32_cloud_block_and_file_storage.png)

## Object Storage in GCP - Cloud Storage

### Playing with Object Storage in GCP - Cloud Storage

To get an idea about object and cloud storage, we'll start with demo.

Go to search > type Cloud Storage and you might see few buckets like below. Bucket is kind of a container for all the objects that you would want to place in cloud storage. We will talk about it in lengths later.

![in28minutes demo image](other/images/cloud_storage/1_cloud_storage.png)

Let's create a new bucket. For that, click on 'Create Bucket'. Now you have to provide bucket name which must be unique globally. 

![in28minutes demo image](other/images/cloud_storage/2_cloud_storage.png)

Next, chose where to store data.

![in28minutes demo image](other/images/cloud_storage/3_cloud_storage.png)

Now choose default storage class

![in28minutes demo image](other/images/cloud_storage/4_cloud_storage.png)

Let's keep other options with default values.

One of the important things to be noticed in here is that there is no mention of the size of the storage that we would want All that we said is that this is the bucket and this is where we want to create it.

Once bucket is created, you may go ahead and store your data in it.

### Exploring Cloud Storage in GCP

![in28minutes slide image](other/images/cloud_storage/5_cloud_storage.png)

In bucket, objects are stored in key-value pair.

![in28minutes demo image](other/images/cloud_storage/6_cloud_storage.png)

In below image, '2030/10/course1.png' is the key and value is the content of course1.png image.

![in28minutes demo image](other/images/cloud_storage/7_cloud_storage.png)

Whenever we are storing files, we will not be updating files bit by bit. So, whenever we want to change any file, we will create a new image and then upload the entire image as such. So, we would be treating the entire object as a single unit. We'll not do partial updates.

### Understanding Cloud Storage - Objects and Buckets

![in28minutes slide image](other/images/cloud_storage/8_cloud_storage.png)

Readings:

- [Storage Options in Google Cloud Platform - Rundown](https://medium.datadriveninvestor.com/storage-options-in-google-cloud-platform-rundown-f78100c4ed37)

### Understanding Cloud Storage - Storage Classes

![in28minutes slide image](other/images/cloud_storage/9_cloud_storage.png)

![in28minutes slide image](other/images/cloud_storage/10_cloud_storage.png)

> Storage classes can also be defined at object level. So, in the same bucket, you can have different objects with different storage classes.

![in28minutes slide image](other/images/cloud_storage/11_cloud_storage.png)

![in28minutes slide image](other/images/cloud_storage/12_cloud_storage.png)

### Understanding Cloud Storage - Uploading and Downloading Options

![in28minutes slide image](other/images/cloud_storage/13_cloud_storage.png)

### Understanding Cloud Storage - Versioning

![in28minutes slide image](other/images/cloud_storage/14_cloud_storage.png)

### Understanding Cloud Storage - Lifecycle Management

![in28minutes slide image](other/images/cloud_storage/15_cloud_storage.png)

![in28minutes slide image](other/images/cloud_storage/16_cloud_storage.png)

To configure the lifecycle for your bucket, go to 'Lifecycle' tab and then 'Add a rule'

![in28minutes demo image](other/images/cloud_storage/17_cloud_storage.png)

![in28minutes demo image](other/images/cloud_storage/18_cloud_storage.png)

![in28minutes demo image](other/images/cloud_storage/19_cloud_storage.png)

### Understanding Cloud Storage - Encryption with KMS

![in28minutes slide image](other/images/cloud_storage/20_cloud_storage.png)

To configure server side encryption, go to 'Configuration' tab of your bucket and click on 'Encryption Type'.

![in28minutes demo image](other/images/cloud_storage/21_cloud_storage.png)

You can also add encryption at the time of creating bucket in 'Advanced Setting' section.

![in28minutes demo image](other/images/cloud_storage/22_cloud_storage.png)

### Scenarios - Cloud Storage

![in28minutes slide image](other/images/cloud_storage/23_cloud_storage.png)

### Playing with gsutil - Cloud Storage from Command Line

![in28minutes slide image](other/images/cloud_storage/24_cloud_storage.png)

![in28minutes slide image](other/images/cloud_storage/25_cloud_storage.png)

## Authentication & Authorization in Google Could with Cloud IAM

### Introduction

- You have resources in the cloud (examples, a virtual server, a database etc).

- You have identities (human and non-human) that need to access those resources and perform actions​.

    - for eg., start, stop or terminate a virtual server

- How do you identify users in the cloud?​

    - How do you configure resources they can access?​

    - How can you configure what actions to allow?

- ***In GCP, Identity and Access Management (Cloud IAM) provides  this service***

    - Authentication - Is it the right user?

    - Authorization - Do they have the right access?

    - Identities can be:

        - A GCP User (Google Account or Externally Authenticated User)​

        - A Group of GCP Users​

        - An Application running in GCP​

        - An Application running in your data center

        - Unauthenticated users​

    - Provides very granular control:

        - Provides very ***granular*** control,

            - to perform single action

            - on a specific cloud resource

            - from a specific IP address

            - during a specific time window

***Scenario***

I want to provide access to manage a specific cloud storage bucket to a colleague of mine.

Important generic concepts:

- Member: My colleague​

- Resource: Specific cloud storage bucket​

- Action: Upload/Delete Objects​

In Google Cloud IAM,

- Roles are set of permissions to perform specific actions on specific resources.

    - Roles do *NOT* know about members. It is all about permissions.

- How do you assign permissions to a member?​
    - By using **Policy**. In policy, you assign (or bind) a role to a member​.

***Solution***

- Choose a *Role* with right permissions (Ex: Storage Object Admin).

- Create policy which binds the member with that *Role*.

> Note
>
> IAM in AWS is very different from GCP.

Readings:

- [Google Cloud IAM and AWS IAM](https://blog.devgenius.io/google-cloud-iam-and-aws-iam-similarities-and-differences-442f2e13835)

### Exploring Cloud IAM Roles

- Roles are permissions:

    - Perform some set of actions on some set of resources​.

- There are 3 types of roles:

    - **Basic Roles (or Primitive roles)** - Owner/Editor/Viewer​

        - Viewer(roles.viewer) - Read-only actions​

        - Editor(roles.editor) - Viewer + Edit actions​

        - Owner(roles.owner) - Editor + Manage Roles and Permissions + Billing
        
        - ***Basic roles are earliest version and not recommended to use in production***
    
    - **Predefined Roles** - Fine grained roles predefined and managed by Google​.

        - Different roles for different purposes​, for examples, Storage Admin, Storage Object Admin, Storage Object Viewer, Storage Object Creator

    - **Custom Roles** - When predefined roles are NOT sufficient, you can create your own custom roles

Readings:

- [Understanding GCP IAM Roles](https://www.strongdm.com/blog/gcp-iam-roles)
- [IAM basic and predefined roles reference - Official Docs](https://cloud.google.com/iam/docs/understanding-roles)

### Playing with IAM Roles - Predefined, Basic and Custom Roles

Let's play with roles. For that, type roles in search bar and press enter. You will be presented with varieties of roles available in GCP. Let's see one role of each category.

![cloud iam - personal](other/images/cloud_iam/1_cloud_iam.png)

**1. Basic Roles**

In filter, type ```Name:roles/viewer``` and you will see more than 2000 permissions are associated with this role. Analyze all such permissions associated with it.

![cloud iam - personal](other/images/cloud_iam/2_cloud_iam.png)

**2. Predefined Roles**

In filter, type ```Storage Admin Object``` and you will see more than 10 permissions are associated with this role. Analyze all such permissions associated with it.

![cloud iam - personal](other/images/cloud_iam/3_cloud_iam.png)

**3. Custom Roles**

Follow [this link](https://docs.cloudera.com/cdp-private-cloud-base/7.1.3/cloud-data-access/topics/cr-cda-create-custom-role-gcs.html) to know how to create custom roles.

### Exploring Cloud IAM - Members, Role and Policy

![in28minutes slide image](other/images/cloud_iam/4_cloud_iam.png)

![in28minutes slide image](other/images/cloud_iam/5_cloud_iam.png)

![in28minutes slide image](other/images/cloud_iam/6_cloud_iam.png)

### Demo - Playing with IAM (DIY)

<ins><strong>GUI</strong></ins>

Below things are covered in this demo:

- In search bar, type **IAM** and try adding a new member, modify present member roles.

- Checkout **Policy Troubleshooter**.

<ins><strong>CLI</strong></ins>

Below are few important commands used to perform IAM related tasks:

![in28minutes slide image](other/images/cloud_iam/7_cloud_iam.png)

### Getting started with Service Accounts

![in28minutes slide image](other/images/cloud_iam/8_cloud_iam.png)

Readings:

- [How to create a service account in the GCP console?](https://support.site24x7.com/portal/en/kb/articles/how-to-create-a-service-account-in-gcp-console)

### Demo - Playing with Service Accounts

**Scenario**

An application is running on VM and we want to give this VM access to create cloud storage bucket.

**Solution**

- Create a service account with role ***Compute Instance Admin*** & ***Storage Admin*** and add users to grant access of this service account if required.

- Create a VM and add this service account.

### Exploring Service Account Use Cases

**Use Case 1 - VM using Cloud Storage**

![in28minutes slide image](other/images/cloud_iam/9_cloud_iam.png)

**Use Case 2 - Connect on premises machine to cloud storage**

Until now, we have been talking about resources which are present in Google Cloud. Now, let's suppose there is a server present outside GCP.

![in28minutes slide image](other/images/cloud_iam/10_cloud_iam.png)

**Use Case 3 - Connect on premises machine to cloud storage but for few hours**

![in28minutes slide image](other/images/cloud_iam/11_cloud_iam.png)

### Scenarios - Service Accounts

![in28minutes slide image](other/images/cloud_iam/12_cloud_iam.png)

### ACL(Access Control Lists) - Part of Cloud Storage

![in28minutes slide image](other/images/cloud_iam/13_cloud_iam.png)

![in28minutes slide image](other/images/cloud_iam/14_cloud_iam.png)

Readings:

- [Access control lists (ACLs) - Official Docs](https://cloud.google.com/storage/docs/access-control/lists)

### Signed URLs - Part of Cloud Storage

![in28minutes slide image](other/images/cloud_iam/15_cloud_iam.png)

Readings:

- [Signed URLs - Official Docs](https://cloud.google.com/storage/docs/access-control/signed-urls)

### Exposing a Public Website using Cloud Storage

Suppose, you want to expose buckets, let's say, in a public website, then below are the steps to do so:

![in28minutes slide image](other/images/cloud_iam/16_cloud_iam.png)

Readings:

- [Make Data Public - Official Docs](https://cloud.google.com/storage/docs/access-control/making-data-public)

## Choosing Database in GCP

![in28minutes slide image](other/images/cloud_database/1_cloud_database.png)

### Understanding Database Fundamentals - Snapshot, Standby etc

![in28minutes slide image](other/images/cloud_database/2_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/3_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/4_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/5_cloud_database.png)

Readings:

- [The Transaction Log](https://learn.microsoft.com/en-us/sql/relational-databases/logs/the-transaction-log-sql-server?view=sql-server-ver16)

### Understanding Database Fundamentals - Availability and Durability

![in28minutes slide image](other/images/cloud_database/6_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/7_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/8_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/9_cloud_database.png)

### Understanding Database Fundamentals - RTO and RPO

![in28minutes slide image](other/images/cloud_database/10_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/11_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/12_cloud_database.png)

### Understanding Database Fundamentals - Read Replicas

![in28minutes slide image](other/images/cloud_database/13_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/14_cloud_database.png)

### Understanding Database Fundamentals - Data Consistency

![in28minutes slide image](other/images/cloud_database/15_cloud_database.png)

### Understanding Database Fundamentals - Choosing Databases

![in28minutes slide image](other/images/cloud_database/16_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/17_cloud_database.png)

### OLTP Relational Databases in Google Cloud - Cloud SQL and Cloud Spanner

![in28minutes slide image](other/images/cloud_database/18_cloud_database.png)

### OLAP Relational Databases in Google Cloud - BigQuery

![in28minutes slide image](other/images/cloud_database/19_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/20_cloud_database.png)

### NoSQL Databases in Google Cloud - Firestone, Datastore and BigTable

![in28minutes slide image](other/images/cloud_database/21_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/22_cloud_database.png)

Readings:

- [NOSQL DATABASE SERVICES](https://datavalley.technology/nosql-database-services-cloud-datastore-cloud-firestore-and-cloud-bigtable/)

### In Memory Database in Google Cloud - Memorystore

![in28minutes slide image](other/images/cloud_database/23_cloud_database.png)

### Databases in Google Cloud Platform - A Quick Review

![in28minutes slide image](other/images/cloud_database/24_cloud_database.png)

### Databases in Google Cloud Platform - Scenarios

![in28minutes slide image](other/images/cloud_database/25_cloud_database.png)

## Exploring Databases in Google Cloud Platform

### Getting Started with Cloud SQL

![in28minutes slide image](other/images/cloud_database/26_cloud_database.png)

### Demo - Playing with CloudSQL

- To begin with Cloud SQL, in search bar, type Cloud SQL and select SQL

    ![in28minutes demo image](other/images/cloud_database/27_cloud_database.png)

- Click on create instance, select the database provider, configure it and create the instance.

    ![in28minutes demo image](other/images/cloud_database/28_cloud_database.png)

- Once your instance is up, create the database.

    ![in28minutes demo image](other/images/cloud_database/29_cloud_database.png)

- To interact with database (performing database related operations like creating tables etc), go to Overview > Connect using Cloud Shell

    ![in28minutes demo image](other/images/cloud_database/30_cloud_database.png)

    ![in28minutes demo image](other/images/cloud_database/31_cloud_database.png)

- Once connected to your database, you can perform your db related tasks.

**Commands Used in this demo**

```
# Cloud SQL
gcloud sql connect my-first-cloud-sql-instance --user=root --quiet
gcloud config set project glowing-furnace-304608
gcloud sql connect my-first-cloud-sql-instance --user=root --quiet
use todos
create table user (id integer, username varchar(30) );
describe user;
insert into user values (1, 'Ranga');
select * from user;
```

### Understanding CloudSQL Features

![in28minutes slide image](other/images/cloud_database/32_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/33_cloud_database.png)

### Getting Started with Cloud Spanner

![in28minutes slide image](other/images/cloud_database/34_cloud_database.png)

### Demo - Playing with Cloud Spanner

- Search Bar > Cloud Spanner > Create Instance

    ![in28minutes demo image](other/images/cloud_database/35_cloud_database.png)

- Configure it as per your requirements.

    ![in28minutes demo image](other/images/cloud_database/36_cloud_database.png)

- In 'Allocate Compute Capacity', you can either choose 'node' or 'processing unit' (it is introduced recently).

- Once cloud spanner instance is created, proceed with the database and table creation.

    ![in28minutes demo image](other/images/cloud_database/37_cloud_database.png)

    ![in28minutes demo image](other/images/cloud_database/38_cloud_database.png)

    ```
    # Cloud Spanner
    CREATE TABLE Users (
    UserId   INT64 NOT NULL,
    UserName  STRING(1024)
    ) PRIMARY KEY(UserId);
    ```

### Getting Started with Cloud Datastore and Cloud Firestore

![in28minutes slide image](other/images/cloud_database/39_cloud_database.png)

### Demo - Playing with Firestore

- Search Bar > Firestore > Select desired mode. Cloud Firestore is the next generation of cloud Datastore. So, if you're creating new projects then the recommendation is to go for Native mode. However, if you have old Datastore projects that you are moving over to Firestore then the recommendation is to go with Datastore mode. ***Remember, once you choose the mode, it will be permanent for your project.***

    ![in28minutes demo image](other/images/cloud_database/40_cloud_database.png)

- Once mode is chosen, select the location, which can be regional or multi-regional.

- After doing all above and click on 'create database' to create the database.

    ![in28minutes demo image](other/images/cloud_database/41_cloud_database.png)

- Now, to add data into the database, click on 'start collection'. A collection is a set of one or more documents that contain data. It is similar to tables in relational database. Once collection is created, to store data, you have to create document under which you can define your fields.

    ![in28minutes demo image](other/images/cloud_database/42_cloud_database.png)

- One of the important things to remember about Datastore or Firestore is the fact that it is hierarchical. It means inside a document, you can add another collection.

### Getting Started with Cloud BigTable

![in28minutes slide image](other/images/cloud_database/43_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/44_cloud_database.png)

### Getting Started with Memorystore

![in28minutes slide image](other/images/cloud_database/45_cloud_database.png)

### Demo - Playing with Memorystore

- Search Bar > Memorystore > Create Instance (for redis or memcached, based on your requirements)

    ![in28minutes demo image](other/images/cloud_database/46_cloud_database.png)

- Provide configuration details and click on create.

### Getting Started with BigQuery

![in28minutes slide image](other/images/cloud_database/47_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/48_cloud_database.png)

### Playing with Cloud SQL, BigQuery and Big Table from Command Line

![in28minutes slide image](other/images/cloud_database/49_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/50_cloud_database.png)

![in28minutes slide image](other/images/cloud_database/51_cloud_database.png)

### Importing and Exporting Relational Databases

Whenever you look at any of the import or export scenarios in Google Cloud platform, you would see that typically cloud storage is involved. Whenever you'd want to move data from somewhere to somewhere, you would first move it to cloud storage and then move it to the destination and that's the reason why you would see that most of these services support export to and from cloud storage.

![in28minutes slide image](other/images/cloud_database/52_cloud_database.png)

### Importing and Exporting NoSQL Databases

![in28minutes slide image](other/images/cloud_database/53_cloud_database.png)

### Databases in Google Cloud Platform - Summary

![in28minutes slide image](other/images/cloud_database/54_cloud_database.png)

## Asynchronous Communication in Google Cloud with Cloud Pub Sub

### Understanding the need for Asynchronous Communication

![in28minutes slide image](other/images/cloud_pub_sub/1_cloud_pub_sub.png)

![in28minutes slide image](other/images/cloud_pub_sub/2_cloud_pub_sub.png)

Readings:

- [Asynchronous Communication — Methods and Strategies](https://dzone.com/articles/asynchronous-communication-methods-and-strategies#:~:text=The%20biggest%20benefit%20of%20asynchronous,also%20lead%20to%20better%20scalability.)
- [Understanding Synchronous and Asynchronous Communication](https://www.microfocus.com/documentation/silk-performer/205/en/silkperformer-205-webhelp-en/GUID-6CC17B5B-71B7-4703-B9E6-C81835A5335A.html)

### Getting Started with Cloud Pub Sub

![in28minutes slide image](other/images/cloud_pub_sub/3_cloud_pub_sub.png)

![in28minutes slide image](other/images/cloud_pub_sub/4_cloud_pub_sub.png)

Readings:

- [What is Pub/Sub?](https://cloud.google.com/pubsub/docs/overview)
- [Google Cloud Pub/Sub – Asynchronous Messaging Service](https://k21academy.com/google-cloud/google-cloud-pub-sub/)

### Exploring Cloud Pub Sub - Publishing and Consuming a Message

![in28minutes slide image](other/images/cloud_pub_sub/5_cloud_pub_sub.png)

![in28minutes slide image](other/images/cloud_pub_sub/6_cloud_pub_sub.png)

### Demo - Playing with Pub/Sub

**[Pub/Sub Demo](https://www.youtube.com/watch?v=f5DOsB7Nlw0&list=PLIivdWyY5sqKwVLe4BLJ-vlh9r9zCdOse&index=3)**

![in28minutes slide image](other/images/cloud_pub_sub/7_cloud_pub_sub.png)

***Few Commands for Reference***

```
> gcloud config set project <project_name>

> gcloud pubsub topics create <topic_name>

> gcloud pubsub subscriptions create <subscription_name> --topic=<topic_name>

> gcloud pubsub topics publish <topic_name> --message=<message_content>

> gcloud pubsub subscriptions pull <subscription_name>

> gcloud pubsub subscriptions pull <subscription_name> --auto-ack

> gcloud pubsub topics list

> gcloud pubsub topics delete <topic_name>

> gcloud pubsub topics list-subscriptions <topic_name>
```

## Private Networks in Google Cloud - Cloud VPC

### Understanding the need for Google Cloud VPC - Virtual Private Cloud

![in28minutes slide image](other/images/cloud_vpc/1_cloud_vpc.png)

![in28minutes slide image](other/images/cloud_vpc/2_cloud_vpc.png)

Readings:

- [Google Cloud VPC (Virtual Private Cloud) for Beginners - K21Academy](https://k21academy.com/google-cloud/google-cloud-vpc/)

### Understanding the need for VPC subnets

![in28minutes slide image](other/images/cloud_vpc/3_cloud_vpc.png)

![in28minutes slide image](other/images/cloud_vpc/4_cloud_vpc.png)

Readings:

- [Subnet Mask - Explained (YouTube)](https://www.youtube.com/watch?v=s_Ntt6eTn94)
- [Subnetting in Networking | Subnetting Examples](https://www.gatevidyalay.com/subnetting-ip-subnetting-examples/)

### Creating VPCs and Subnets in GCP

![in28minutes slide image](other/images/cloud_vpc/5_cloud_vpc.png)

![in28minutes slide image](other/images/cloud_vpc/6_cloud_vpc.png)

![in28minutes slide image](other/images/cloud_vpc/7_cloud_vpc.png)

Follow below links to see the creation of VPCs in GCP

- [How to Create VPC (Virtual Private Cloud) Network in GCP - linuxtechi](https://www.linuxtechi.com/create-vpc-network-in-gcp-google-cloud/)
- [VPC Creation on Google Cloud Platform(GCP) - Medium](https://medium.com/petabytz/vpc-creation-on-google-cloud-platform-gcp-67fa397c1106)

Readings:

- [CIDR Range Visualizer](https://cidr.xyz/)

### Understanding Firewall Rules in GCP

![in28minutes slide image](other/images/cloud_vpc/8_cloud_vpc.png)

![in28minutes slide image](other/images/cloud_vpc/9_cloud_vpc.png)

### Getting Started with Shared VPC

![in28minutes slide image](other/images/cloud_vpc/10_cloud_vpc.png)

### Getting Started with VPC Peering

![in28minutes slide image](other/images/cloud_vpc/11_cloud_vpc.png)

### Implementing Hybrid Cloud with Cloud VPN and Cloud Interconnect

![in28minutes slide image](other/images/cloud_vpc/12_cloud_vpc.png)

![in28minutes slide image](other/images/cloud_vpc/13_cloud_vpc.png)

![in28minutes slide image](other/images/cloud_vpc/14_cloud_vpc.png)

Readings:

- [Configuring a Shared VPC on GCP - VMware Tanzu Docs](https://docs.pivotal.io/ops-manager/2-10/install/gcp-shared-vpc.html)

## Operations in Google Cloud Platform

In this section, let's look at how you can perform operations in the cloud. Developing applications is important.
However, maintaining applications and maintaining them in production is very important as well. That's where monitoring, logging, tracing, debugging, and all these kind of things become really, really important.

### Getting Started with Google Cloud Monitoring

![in28minutes slide image](other/images/cloud_operations/1_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/2_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/3_cloud_operations.png)

Readings:

- [Getting started with Cloud Monitoring](https://www.youtube.com/watch?v=wY8cmFY4ua8)

### Getting Started with Google Cloud Logging

![in28minutes slide image](other/images/cloud_operations/4_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/5_cloud_operations.png)

### Exploring Google Cloud Logging - Audit Logs

![in28minutes slide image](other/images/cloud_operations/6_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/7_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/8_cloud_operations.png)

### Exploring Google Cloud Logging - Routing Logs and Exports

![in28minutes slide image](other/images/cloud_operations/9_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/10_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/11_cloud_operations.png)

Readings:

- [Understand your services with Cloud Logging](https://www.youtube.com/watch?v=IlUCyV8mcS0)

### Creating a Cloud Storage Bucket and Cloud Function

This is a practice section where you need to create a bucket and then associate a cloud function to it which will be triggered as soon as any object is uploaded to this bucket. In this cloud function you can do implement anything which generates a log when an object is uploaded to bucket.

The whole purpose of this exercise is to demonstrate the cloud logging.

### Getting Started with Google Cloud Trace

![in28minutes slide image](other/images/cloud_operations/12_cloud_operations.png)

Readings:

- [Cloud Trace - GCP](https://cloud.google.com/trace#:~:text=Cloud%20Trace%20is%20a%20distributed,near%20real%2Dtime%20performance%20insights.)

### Getting Started with Google Cloud Debugger

![in28minutes slide image](other/images/cloud_operations/13_cloud_operations.png)

### Cloud Profiler and Error Reporting

![in28minutes slide image](other/images/cloud_operations/14_cloud_operations.png)

![in28minutes slide image](other/images/cloud_operations/15_cloud_operations.png)

### Scenarios - Operations in GCP

![in28minutes slide image](other/images/cloud_operations/16_cloud_operations.png)

## Organizations and IAM - Organizing Google Cloud Resources

### Organizing Google Cloud Resources - Projects, Folders and Organization

![in28minutes slide image](other/images/cloud_organisation_and_iam/1_cloud_organisation_and_iam.png)

![in28minutes slide image](other/images/cloud_organisation_and_iam/2_cloud_organisation_and_iam.png)

> Note
>
> In a free tier, we don't have organization and folders. We directly create projects.

Readings:

- [Resource hierarchy - Official Docs](https://cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy)

### Exploring Billing Accounts

![in28minutes slide image](other/images/cloud_organisation_and_iam/3_cloud_organisation_and_iam.png)

![in28minutes slide image](other/images/cloud_organisation_and_iam/4_cloud_organisation_and_iam.png)

### Understanding IAM Best Practice

![in28minutes slide image](other/images/cloud_organisation_and_iam/5_cloud_organisation_and_iam.png)

### Understanding User Identity Management in GCP

![in28minutes slide image](other/images/cloud_organisation_and_iam/6_cloud_organisation_and_iam.png)

![in28minutes slide image](other/images/cloud_organisation_and_iam/7_cloud_organisation_and_iam.png)

### Exploring IAM Members and Identities

Let's look at different types of IAM Members or Identities:

![in28minutes slide image](other/images/cloud_organisation_and_iam/8_cloud_organisation_and_iam.png)

![in28minutes slide image](other/images/cloud_organisation_and_iam/9_cloud_organisation_and_iam.png)

Readings:

- [Overview of Cloud Identity](https://cloud.google.com/identity/docs/overview)
- [Single Sign-on vs. Federated Identity Management](https://www.pingidentity.com/en/resources/blog/post/sso-vs-federated-identity-management.html#:~:text=Federated%20identity%20management%2C%20also%20known,and%20authenticate%20users%20across%20domains.)

### Understanding Organization Policy Service

![in28minutes slide image](other/images/cloud_organisation_and_iam/10_cloud_organisation_and_iam.png)

> Note
>
> Organization policy always overrides whatever is configured in IAM. So, if an organization policy prohibits the creation of resources in, let's say, a specific region even though a user might have that access through IAM, he will not able to create the resource in that specific region because Organization policy has the highest priority.

### Exploring IAM policy at multiple levels - Resource Hierarchy

![in28minutes slide image](other/images/cloud_organisation_and_iam/11_cloud_organisation_and_iam.png)

Readings:

- [What is Identity and Access Management in Google Cloud?](https://www.educative.io/answers/what-is-identity-and-access-management-in-google-cloud)

### Exploring IAM Predefined Roles - Organization, Billing and Project

![in28minutes slide image](other/images/cloud_organisation_and_iam/12_cloud_organisation_and_iam.png)

![in28minutes slide image](other/images/cloud_organisation_and_iam/13_cloud_organisation_and_iam.png)

![in28minutes slide image](other/images/cloud_organisation_and_iam/14_cloud_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Compute Engine

![in28minutes slide image](other/images/cloud_organisation_and_iam/15_cloud_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google App Engine

![in28minutes slide image](other/images/cloud_organisation_and_iam/16_cloud_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Scenarios

![in28minutes slide image](other/images/cloud_organisation_and_iam/17_cloud_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Kubernetes Engine

![in28minutes slide image](other/images/cloud_organisation_and_iam/18_cloud_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Cloud Storage

![in28minutes slide image](other/images/cloud_organisation_and_iam/19_cloud_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Cloud BigQuery

![in28minutes slide image](other/images/cloud_organisation_and_iam/20_cloud_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Logging Service Accounts

![in28minutes slide image](other/images/cloud_organisation_and_iam/21_cloud_organisation_and_iam.png)

### Other Important IAM Roles

![in28minutes slide image](other/images/cloud_organisation_and_iam/22_cloud_organisation_and_iam.png)

### SSHing into Linux VMs

![in28minutes slide image](other/images/cloud_organisation_and_iam/23_cloud_organisation_and_iam.png)

![in28minutes slide image](other/images/cloud_organisation_and_iam/24_cloud_organisation_and_iam.png)

### Exploring IAM Scenarios

![in28minutes slide image](other/images/cloud_organisation_and_iam/25_cloud_organisation_and_iam.png)

## Exploring Google Cloud Platform - GCP - Pricing Calculator

![in28minutes slide image](other/images/cloud_pricing_calculator/1_cloud_pricing_calculator.png)

Click here to access [Google Price Calculator](https://cloud.google.com/products/calculator).

## Google Cloud Platform - Other Important Services

### Getting Started with Cloud Deployment Manager

![in28minutes slide image](other/images/cloud_other_imp_services/1_cloud_other_imp_services.png)

![in28minutes slide image](other/images/cloud_other_imp_services/2_cloud_other_imp_services.png)

### Understanding Cloud Deployment Manager

![in28minutes slide image](other/images/cloud_other_imp_services/3_cloud_other_imp_services.png)

![in28minutes slide image](other/images/cloud_other_imp_services/4_cloud_other_imp_services.png)

![in28minutes slide image](other/images/cloud_other_imp_services/5_cloud_other_imp_services.png)

### Getting Started with Cloud Marketplace

![in28minutes slide image](other/images/cloud_other_imp_services/6_cloud_other_imp_services.png)

### Getting Started with Cloud DNS

![in28minutes slide image](other/images/cloud_other_imp_services/7_cloud_other_imp_services.png)

![in28minutes slide image](other/images/cloud_other_imp_services/8_cloud_other_imp_services.png)

### Getting Started with Cloud Dataflow

![in28minutes slide image](other/images/cloud_other_imp_services/9_cloud_other_imp_services.png)

Readings:

- [Google Cloud Dataflow](https://www.zuar.com/blog/what-is-google-cloud-dataflow/)

### Getting Started with Cloud Dataproc

![in28minutes slide image](other/images/cloud_other_imp_services/10_cloud_other_imp_services.png)

Readings:

- [What is Dataproc?](https://cloud.google.com/dataproc/docs/concepts/overview#:~:text=Dataproc%20is%20a%20managed%20Spark,you%20don't%20need%20them.)

## References

- [GCP Associate Cloud Engineer - Google Cloud Certification - in28Minutes Official, Ranga Karanam | GCP Certification - Google Cloud Engineer & Architect](https://www.udemy.com/course/google-cloud-certification-associate-cloud-engineer/)