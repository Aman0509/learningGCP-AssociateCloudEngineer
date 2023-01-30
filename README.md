# GCP - Associate Cloud Engineer

## Resources and Useful Links

- [Google Cloud Associate Cloud Engineer - Resources](https://www.in28minutes.com/google-cloud-ace-resources)

- [ExamTopics - Preparation for the Exam](https://www.examtopics.com/exams/google/associate-cloud-engineer/)

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

- [Getting Started with Google App Engine](#getting-started-with-google-app-engine)

    - [Understanding App Engine Environments - Standard & Flexible](#understanding-app-engine-environments---standard--flexible)

    - [Understanding App Engine Components Hierarchy](#understanding-app-engine-components-hierarchy)

    - [Comparing App Engine Environments - Standard vs Flexible](#comparing-app-engine-environments---standard-vs-flexible)

    - [Scaling Google App Engine Instances](#scaling-google-app-engine-instances)

    - [Playing with App Engine in GCP - Google Cloud Platform](#playing-with-app-engine-in-gcp---google-cloud-platform)

    - [Exploring App Engine App, Services and Versions](#exploring-app-engine-app-services-and-versions)

    - [Splitting Traffic between Multiple Versions in App Engine](#splitting-traffic-between-multiple-versions-in-app-engine)

    - [Create a New Service and Playing with App Engine](#create-a-new-service-and-playing-with-app-engine)

    - [Understanding App Engine's app.yaml](#understanding-app-engines-appyaml)

    - [Understanding Request Routing in Google App Engine](#understanding-request-routing-in-google-app-engine)

    - [Deploying New App Engine Versions without Downtime in GCP](#deploying-new-app-engine-versions-without-downtime-in-gcp)

    - [Splitting Traffic between App Engine Version in GCP](#splitting-traffic-between-app-engine-version-in-gcp)

    - [Exploring App Engine and GCloud - GCloud App](#exploring-app-engine-and-gcloud---gcloud-app)

    - [Exploring App Engine and GCloud - GCloud App Instances](#exploring-app-engine-and-gcloud---gcloud-app-instances)

    - [Exploring App Engine and GCloud - GCloud App's Services & Versions](#exploring-app-engine-and-gcloud---gcloud-apps-services--versions)

    - [Creating Cron Jobs in App Engine](#creating-cron-jobs-in-app-engine)

    - [Exploring App Engine YAML Files - dispatch and queue](#exploring-app-engine-yaml-files---dispatch-and-queue)

    - [Important Things to Remember - Google App Engine](#important-things-to-remember---google-app-engine)

    - [Scenarios - Google App Engine](#scenarios---google-app-engine)

- [Getting Started with Google Kubernetes Engine](#getting-started-with-google-kubernetes-engine)

    - [K8s Journey - Creating a GKE Cluster](#k8s-journey---creating-a-gke-cluster)

    - [Understanding Kubernetes Clusters - Google Kubernetes Engine](#understanding-kubernetes-clusters---google-kubernetes-engine)

    - [Getting Started with Google Container Registry(GCR)](#getting-started-with-google-container-registrygcr)

    - [Important Things to Remember - GKE](#important-things-to-remember---gke)

    - [Scenarios - GKE](#scenarios---gke)

    - [Quick Review - Command Line - gcloud container clusters](#quick-review---command-line---gcloud-container-clusters)

    - [Quick Review of GKE & K8s](#quick-review-of-gke--k8s)

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

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1WrMoSMzogSMpRisec0BQdifJ_yk59Awm)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1uQjQWu0kcgt7OdqY4I1wz0bYsq8kmOw9)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1FzaQGH6GTQCmFh5g1JjExpwxqOwQ68Az)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1fVY7k2XcjatISsd2btYb1YAF_Bjx0aiH)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=12YQde3IxWqo3kBaJch_KoRISd_756thn)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1nGR4Em-iOHSoXgUJlew4RS5gXJ0eppBQ)

## Google Cloud Regions and Zones

### Need for Regions and Zones

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1QqJbb6s7Ev7q0GSyRDU30OVviDEOEzFO)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1upPHICA6aj2KHLmFF5Rhgb_ZGkQZaOHE)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1311awyFihNhqIu45kE64RiVYyPyCWovM)

### Understanding Regions and Zones in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1nbtAyiqz-S_eo2thGLvbJVTFKOwSwRU0)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1X3kBTs7wtRoNvNHkmpUmfimV8HTLsKbk)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1pnMbKpMqg94DQPKl5XO5VEiGI74mvfFE)

## Google Compute Engine for Associate Cloud Engineer

### Getting started with Google Compute Engine - GCE

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1uLbBQNpJ9jtgvbzXUKJjyKemtv5orIx7)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1_iER8r9X3WV8m1s2x3SF8VJiWlDlkB0b)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1SkxfFFYSkwYdBKOd6wwXzOGDWi7LScgG)

- Go to search bar > type 'compute engine' and hit enter > create

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1aWhxyoHQP2ZdoTi7g_I5svpOZj1EgDyW)

- Provide configurations like, name, region, machine type, os details etc and then click on create.

Readings:

- [Creating a Virtual Machine Instance with Google Cloud](https://www.waferwire.com/blog/creating-a-virtual-machine-instance-with-google-cloud/)

- [Create a Google Compute Engine stack](https://www.koding.com/docs/creating-a-gce-stack)

### Understanding Machine Types and Images in Google Compute Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1wXjWiIkOhQBdwJZn0K5P09GMaKdWLtkb)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1o7hJvccCZoUw5ao9Swm3Ey9SrBwr0P6h)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1YBwNJg6i3VBN_9oZCqG7aMaxBC4G8EKw)

### Installing HTTP Webserver on GCE VM

- Once VM is created, install Apache in it and inside the index page, let's just keep the VM's hostname and IP address.

    ![in28minutes slide image](https://drive.google.com/uc?export=view&id=1_GvELP9FwrL5z6XntUq5NCdY3NJ7T8eo)

- To launch the index page hosted on VM, use the **External IP**. Make sure you have allow the HTTP/HTTPS traffic on this VM.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=11s7hHLfoW_1cfkug-d9R-elyDIgYou7l)

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1-RqrniDYAiEfQEVgxSIgqIMgR_4YCw-f)

### Understanding Internal and External IP addresses

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1kai69AKgBvUgKVvz-bPmq8gKwsZuSuUf)

### Playing with Static IP Addresses

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1OLaNGf7TMNkReQ-MgDC-huJpLMg9vVMh)

- Go to Search bar > type **External IP Addresses** > list of all external IP addresses can be found here which are assigned to VMs

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1Ptd5hj654ykbzdlMs4piTxph8MZmX3nQ)

- Now to reserver an IP or create a static IP, click on **Reserve Static Address** and provide the configurations.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1JM-_t0ZN0D3jvNGc7ejQvaGltUc2RUPe)

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1jfx5dowTc0W6oJ_bprxd05o3CcTDDrM2)

- Once static IP is created, it needs to be assigned to the VM. For that, click on **change** and select the VM.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1Fbnf37TzjcTcWvHszVkzWJhOIZr9WIEf)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1cM9uoS9nb8OGVJZIgFSuEbOMSoz4CED2)

### Simplifying the Web Server setup with Compute Engine Startup Script

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Y8bZTsljfbA3U10urA8rUAuL5wz7-AWO)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1tTkl80tCC7KsdzKqo13AcjLgeeV_RTkr)

We will configure our startup script during VM creation. For that, while creating VM and configuring options, go to **Management** > under **Automation**, you will find **Startup script** text area. Update your script there and create instance.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1DiBMHXsUFlZRK0AgnePKzIjlDnyH-vlA)

To test it, click on external IP and verify everything's working as expected.

### Simplifying VM creation with Instance Templates

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1z8eJc8Pg1RujVLdp95scFmJe_4YdXgbX)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=15FD20XNSovzFPJFllOM3EC1onIXD6zeJ)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1ZeQeVUjPYpXEIsk0OkW6gAz7Bta1sQ_b)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1GmdU6TkSjYp0W8nyPdgIAqlRJAvygwNZ)

Click on create and new instance template will be created. Based on it, now, VMs can be created.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1pcyF1WR-G5HOTe-Gy9h33_CFBBJikNcc)

### Reducing Launch Time with Custom Images

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1DWFlv6chivTW6AipbevQsNvCWnY3J9rl)

To create image from a disk, ensure VM instance attached with that disk should be in stopped state.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1OV0oZ-jfByLneXMrNug15i54Xcf-XumI)

Provide all required configurations and click on create. Once created, you can find it under **Images** tab.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1lxy6UHwBCkvn_rfcjSzL2GgwWefm-vtm)

Now, you can create an instance template and use this custom image under boot disk section and create VM instances based on this template.

## Google Compute - Optimizing Costs and Performance in GCP

### Understanding Sustained Use Discounts in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1WAIghO06udmc3fJiHM7auHbAe9IU99mQ)

### Understanding Committed Use Discounts in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1PdC069s8TsPoXyQbIwvZ07z37FdmNuFG)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1ezyOSelTEihlhs-XdOfl5lnCSMv7rsgW)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1g15ieMdMR4sKu0OcP7NTcI-rDpaDGBkd)

### Saving Costs with Preemptible VMs

![in28minutes slide image](https://drive.google.com/uc?export=view&id=15aIHh6BNuztvGAExRk6JovcLO6duzD3r)

Proceed with the VM creation and select under **Management, security, disks, networking, sole tenancy**

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1DzBsfwPpN34Pf8W8J5LnG3OwRkqFRcl-)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1zjYJvejHa76scT7iTScdL16RTt7oPgGN)

### Quick Update about Spot VMs

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1NrAYySIcAakWGQ8jJKlMiG9jTv07DG_p)

### Understanding Billing for Google Compute Engine VMs

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1aD39aIHRYJjWVhJ_HDjx_oOLta0WXWIS)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=11dJdga-gSl8OdcaoXhdQmUyubcVYkFV7)

Click on 'Create Budget' and configure as per your requirements.

### Achieving High Availability with Live Migration and Automatic Restart

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1rzFiQyF_o5kyyNwUH1P7XJ8Xs-Bqxr7z)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1Jov16XgKAs2OiSdaG2zo6z6HHGRqkwGT)

### Understanding Custom Machine Types

![in28minutes slide image](https://drive.google.com/uc?export=view&id=13g09L0a9pPxMX-DkntQ0JnIS8lCVTb-y)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1RfxZGnsfIIPIVPKANKBEIYGkfSLJgTLH)

### Exploring GPUs in Google Compute Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1xAru82w5XY9ynUNTo8evW4RbemiA6Rjt)

There are 2 ways of creating GPU machines:

**1st Way**

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1m5MnNaREdtD3Hgh8u1LGE_dS71-1iFda)

**2nd Way**

Select machine type and then add GPU to it.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1nKyJ9PgD047m7jHI3yofJzv-9YcQtTqY)

### Quick Review - Virtual Machines in Google Cloud Platform

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1h8Z6nLtWxu53M_pdLsF1DOflQmxWIi17)

### Best Practices - Virtual Machines in Google Cloud Platform

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1fre3DdmG70vprMPbi-ke7XDOgFHOHHAH)

### Scenarios - Virtual Machines in Google Cloud Platform

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1gaBfAEkRdBs6OZiE7TFJOz1hF3JN7zBU)

### Quick Review - Google Compute Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Ks1nwnrX17EjwPSQgpVPv57ha4rVf7cZ)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1EWAKoAM54VvaCJ1MLZMGo2Duy-Bj-sOD)

## GCloud for Associate Cloud Engineer

### Getting Started with GCloud

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1i-kj6JP7rGgOlr1sKlRvmdgSXZ-_tEz3)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1eJnLEJaOmiGWgmYHzjDJvBbyhKhVTDLS)

### Playing with GCloud Config Set

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1XEUMUWWQE2NjoMjLcu1AjiZ9XTLQLq6z)

### Managing Multiple Configurations in GCloud

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ApSaUE8dTeI3B3IrJV_Q_hc33nlS-tTW)

### Understanding Command Structure in GCloud to play with Services

![in28minutes slide image](https://drive.google.com/uc?export=view&id=13nTigSnF8bEpyK98dL8O3OugwpWAOWDg)

### Playing with GCloud Compute Instance Create

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1iQiPg0tp7AWYMkFHptew7kvLg2zRgoa7)

### Setting Default Region and Zone for Compute Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1S1t_lDuh15Ngi8NlZDebjzyOHU589PjX)

### Exploring GCloud Commands - list and describe

![in28minutes slide image](https://drive.google.com/uc?export=view&id=152-3PU7aoRpz1A0TNQpWdhgWAchwF8BN)

### Playing with Compute Instances in GCloud

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1NBof-6n76RtdWkTQedudPxaM_5rnt7OC)

### Playing with Instance Templates in GCloud

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1EAkywAH6b0iXVUfWzQ3wCcgUGWxSokdJ)

## Getting Started with Instance Groups

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1lzzDPiUUQLEqgv7q3tn9Gcu2akzKu2vX)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1msc-P0zKH8TrHY-hXKIRkTIylC7roP2z)

### Creating Managed Instance Groups (MIG)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1-FjJlDa176zVTLf96-0xJuIHU2koa-aG)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1MlDWl7FWf9iSlzM3AsEX9Y0KUE0xiNXS)

Provide configurations as per your requirements and click on create.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1tvy8L5rfMPY9ptdeP8wrFCHVCA1P8uZg)

### Updating a MIG - Rolling Update and Restart

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ig0BgvQ-atsM-f5zzjvGcg5XRhYVtR_j)

**Rolling Update**

To configure rolling update, go to instance groups > update VMs

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1yDoPpYWToBXnRwoD_scRbaqMKXB2QK_Z)

In this scenario, let's say you want this MIG to run on different Instance template. In summary, you want to update the instance template.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1cGhQMjy8K_sJVoj4xPzHbOPG7T5OcqBF)

After that, select type update. With ***Automatic*** update type, you've few more configure options to select.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1oTYefHuM00heZ-V3zNHiD0eEdK7KHHte)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1S-XUtulam0m01PR_IvPNDRvpbfM_aGzh)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1qo3A2SmtGjfFBTZWI8ExKI9S60OUGfMs)

**Rolling Restart**

![in28minutes demo image](https://drive.google.com/uc?export=view&id=15dCanJMXmlReT40pAfuy9rvbkrk2ljtm)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1J9x0E48zDAlNxLllYCOdDBIrBWT_tI5A)

### Scenarios - Instance Groups

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1sT3wpCf9YvM-4nJb-ArxweuJlrv6csOt)

### Using GCloud to play with MIG

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1WsI-nqVci73reitqNysW6uRXs656J7Fz)

### GCloud and MIG - Making Updates

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1xiR8hLjSuWuKwcIiv_k0C74D7vVVZjTS)

### GCloud and MIG - Managing Templates Updates

In the last section, we looked at a few ways to make updates to our managed instance group and it was concluded with setting of instance template. However, one thing that we did not discuss is when would the template be updated? Will it be updated immediately?

Note that the manage ***instance group configuration*** would be updated immediately, but would the instance be immediately updated to that template? Will there be any downtime while making the update to that specific template?

The answer to that is after updating the instance template you can configure how to do the update. How do you roll out the new template to the existing virtual machines?

There are multiple commands that you can make use of. You can make use of the *recreate-instances* and the *update-instances* that we have used earlier. Or there is another set of command which you can use called *rolling-action start-update*.

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1YExzqSkw3HghMmyNdar_hhjLum7Od9O9)

When you're doing *recreate-instances*, you are doing everything manually. However, you can also automate the upgrade to the new version template in a more controlled fashion using *rolling-action start-update*.

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1jidt1QKpUpiNaeH191m8xVq45BO2rmXV)

## Load Balancing in GCP

### Getting Started with Cloud Load Balancing

![in28minutes slide image](https://drive.google.com/uc?export=view&id=12exRtMYoeuBwJscJY9K_icKekBXDwN3t)

### Understanding HTTP, HTTPS, UDP and TCP Protocols

![in28minutes slide image](https://drive.google.com/uc?export=view&id=12HkTxXZPxFwQxRjQZvZdMjYdaXIQKtLU)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1GZO8FGfMaUs228SkZ26r8EC09tdhVgdc)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1p_MZ7QAF70o3lF6C34CtcuvUpRMobCj7)

Readings:

- [OSI Model Layers and Protocols in Computer Network](https://www.guru99.com/layers-of-osi-model.html)

### Creating a Load Balancer in GCP

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1rmoVf_UaBhiA7dZofv05OqIQcxhTBfmT)

Select type of load balancing as per your requirement.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1tJUH8QnpAdzNOcas8xFqLFPBKYOhklX9)

Let's create a HTTP(s) load balancer. For that, click on *Start Configuration* and provide configurations.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1I9Mu0qANDvF645-BocwfdpWR2Q7_mQEo)

Click on *Continue* and configure backend, host and path rules and frontend.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1VB-WizKjfrRIx5JHW6P1YZbPxoAax9tW)

### Understanding Cloud Load Balancing Terminology in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1tAAVKzTclSjqUtdTpZfBb_dRqavrn8Ek)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1MRLya9o1IQrhT0Z9TJxRtrHxO6VuMeUO)

Readings:

- [Cloud Load Balancing overview](https://cloud.google.com/load-balancing/docs/load-balancing-overview)

### Choosing a Load Balancer in GCP

![google cloud docs image](https://drive.google.com/uc?export=view&id=13HDerwLtHAjw8sZUtFn-U4ZaplrCmY47)

Readings:

- [Choose a load balancer](https://cloud.google.com/load-balancing/docs/choosing-load-balancer)

### Explore Features of Load Balancers

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1kZKh9UPW1OGmA1QrNasmBcgsdPLpTO4L)

### Scenarios - Cloud Load Balancing

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1pHbhAfHJVwZl7n91j5o_hPFvtqrMxEow)

## Managed Services in Google Cloud Platform

### What are Managed Services?

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1bjmATeNbD_zjryEugPLvif_9Tz7k81HT)

### Understanding IAAS and PAAS

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1yr0ga_FOk750GD-4aHTIg17AMkGOUcsk)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1anQ1G51YzZ8Z3LzrlFTovJCRVMOA0YwN)

### Understanding Evolution to Containers and Containers Orchestration

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1dtBVSbdZWz5upS1rSC-CfULXpaTESgWb)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=12x37ktt_dbXWtunYvosEB86QvHrEOof7)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Uo5gezFUbHF3NWYcG-j0z0JojfcQIfKK)

### Understanding Serverless

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1vXlKc1BktgLWPoIEct9WIiFSJmVQ1yCm)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Siqv2mVH5ai--IAr4QwHYcJMUnvMeA-E)

### Exploring Google Cloud Platform GCP Compute Services

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1qA0x2X1CrfYGFaQx1cGa8typNA_vo_PB)

## Getting Started with Google App Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14oYYgq7LSqX1PHE5D1b2oYh8r1nCYolI)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ZawOmpUlW1u2qZvKHavVTPBo8P5MUY1-)

### Understanding App Engine Environments - Standard & Flexible

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1a2pvjsFAaU2PsQrQi3cSXdTGBVVJiPRA)

### Understanding App Engine Components Hierarchy

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1A1h6rNoQUuXHr_xic2868duLrr7pqKf0)

### Comparing App Engine Environments - Standard vs Flexible

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1icOtQ7zH_VhBgF5N6qPMecPBGT2erpFN)

### Scaling Google App Engine Instances

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Aw8pxQzBY7hCZdciTafUF8787V5M8ka8)

### Playing with App Engine in GCP - Google Cloud Platform

- Go to search bar > type 'App Engine' > click on 'Create application'

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1_L3aWUyVBgFh1AiOR0Hv6WVcANs0PJxD)

- Select Region and click on 'Create app'

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1QNyqfFNd-3mTkAg4lTm3455YJYBQR5q3)

- Select language and environment and click on 'Next'

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1NWKkcIPwSBabLIPhCbLyQmsHnzLUJEPA)

- App engine app will be created successfully.

- Now to deploy service to this app, you can either use GCloud SDK or cloud shell. Let's use cloud shell.

- For demo purpose, let's write simple Python flask program via inbuilt editor in cloud shell (focus only on code inside default-service directory for now).

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1dGKqZqj3wRONWIdndVshXr8AY0HwDeSR)

- Inside `app.yaml`, you have application configuration required for App Engine. For instance, 'runtime' is one of the configuration which tells App Engine about the application environment.

    ```
    runtime: python39
    ```

- To deploy, use command, `gcloud app deploy`. Ensure, you are on the right project.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1MF2VuS0tpZA7kM-a6coBqzrtWvM2uQOH)

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1iL4Sej_jiA1W4WkEWqKf6M9MjKvoROO0)

- In this deployment, we didn't specify the service name, so it will be deployed as default service. Also, we didn't specify the default service for this specific deployment.

- Once this deployment is successful, you can go to the URL at which your app is exposed and check if it is working fine.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1YnV_ObQrQWD64yXI2WV4eL9CZ7wAT2Zs)

### Exploring App Engine App, Services and Versions

**App Dashboards**

In App Dashboards, you have can see metrics and summary.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1H2ZLXU8gmr1b2jWb8ObaGuZn_Ya5l6tk)

**Services**

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1ReldF0eR_6VB04dlAs099PFnEAQOYAE8)

**Versions**

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1Ftnt3r4k-HSc27cfer4fcUdmL-69cA_A)

You can also get above information using commands:

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1FQrayxfJ9rK3qBt0AmAbmlSx6pDI2ef1)

Now, let's say you want to deploy another version of it. For that, you can do it like below:

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1iiKb-hgU4Yp9qMG9sgAmqiJQsR8YFyr_)

During the next version deployment, your application will keep on running of current version. So, there will be no downtime. As soon as the next version is deployed. Traffic will be shifted to the new version.

To find out the link of this version (or active version), you can use `gcloud app browse` command. However, to find out the link for specific version, just add `--version=<version>` flag.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1VDEI1mIRAg_4TswqTQLVHyvC2L7KonXP)

### Splitting Traffic between Multiple Versions in App Engine

Previously, we had seen that after deploying new version, full traffic was automatically shifted to it. However, sometimes, you really don't want this rather slowly transfer the traffic to new version after doing some testing.

Let's suppose, currently our app is running on **v2** and now, we are updating it to **v3**.

`--no-promote`, it will disable the transfer of all traffic to the newly deployed version.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=13bnPfUAFkSvqMolfuDFNPkvcA76WMA_E)

After verifying that everything is working fine. You can now shift or split the traffic between multiple versions.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=160bA8UtOe254WM7MzPbyDZi0iTOBfuyV)

Readings:

- [gcloud app services set-traffic](https://cloud.google.com/sdk/gcloud/reference/app/services/set-traffic)

### Create a New Service and Playing with App Engine

In addition to the default service, you can create the multiple services. In our example, we will create the new service whose code is inside `my-first-service`. We will deploy the same. After deploy, new service is created with it's first version.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1rG-izTMtUCWy8e4-NeGl8XTO2CBpOo_A)

If you check the services, you will find 2 services running.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1wYks0JVAsWD6e3LkFpwTlWEZfd566kz9)

To find the link for the new service's version, do like below:

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1qOodEtqnVz-9nPSvqekwTAe_CiYDqUwB)

Just add `--version` flag if you are looking for a specific version of that service.

### Understanding App Engine's app.yaml

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1gEdNqwcXVo92l6ipH5kBT0ggfLeIoyTa)

### Understanding Request Routing in Google App Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1SfcQGRSvMon7gnhOBj0B0aqsuKcnPHL-)

### Deploying New App Engine Versions without Downtime in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=104QXkrO3gmhdF94oQsJhMeUFxs6WHtJB)

### Splitting Traffic between App Engine Version in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1MUzOBvakyFIL_ixHK9uBpjRLxUrHGH9a)

### Exploring App Engine and GCloud - GCloud App

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1tTLvSmdIWW472mLzeaOFj_5sZ3EKx1A_)

### Exploring App Engine and GCloud - GCloud App Instances

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1xHu8e8x1N7uiE1WDpC7zExA3NTAVKZxq)

### Exploring App Engine and GCloud - GCloud App's Services & Versions

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14VCa4VoXcRFxHjzwlR30o5HV8orskDgi)

### Creating Cron Jobs in App Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1wRjLpKiPtvio4IxepMAlj9SErUUIKiMM)

### Exploring App Engine YAML Files - dispatch and queue

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1zW4F0rrCQXsehxCzLjxmAMm7fILQ-WZT)

### Important Things to Remember - Google App Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1oqghK0N6kRtASK21Q_R-GdZK7P4sIHv_)

### Scenarios - Google App Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11ifsk3gInK1vj6GVBXGymKl009vHMZQo)

## Getting Started with Google Kubernetes Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1nrBYVojYHSla9IZDtj0wg9EYxomgFl_T)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1_W7aN3ccYhUppbfqLcn34dF4u_HwUUtR)

### K8s Journey - Creating a GKE Cluster

In search bar, type 'Kubernetes Engine' > Create Cluster

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1rIaBTC1TmYDsbwsVGHCAfKZsXLIUrsom)

You will 2 cluster modes

![in28minutes demo image](https://drive.google.com/uc?export=view&id=13HCviSZ7sJDVUCk9yrrlhECMDsv4EF9r)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1L-aA1SI_Ktq1FyaeJWf_YuonjMPXejUm)

For now, click on the standard, provide the configurations and click on create.

Now, once cluster is created successfully, connect to it and you can perform K8s related tasks using `kubectl` CLI.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1rUPg1aUeyWIqN0kiTf1c2q7L5EOmwuv8)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1vII6ZojFiCKv37twwkhC2LNaFIfX9ojo)

Readings:

- [Types of clusters](https://cloud.google.com/kubernetes-engine/docs/concepts/types-of-clusters#:~:text=the%20Autopilot%20overview.-,Cluster%20configuration%20choices,best%20for%20your%20production%20workloads.)

- [Google Kubernetes Engine](https://tutorialsdojo.com/google-kubernetes-engine-gke/)

### Understanding Kubernetes Clusters - Google Kubernetes Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1P2pbpBXviEGB12_ZPV5MQv1_503yKrKs)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1_ukgJsp2MSl0HxiWR0la3rmgSEKrr8Pm)

### Getting Started with Google Container Registry(GCR)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1JnlPBKvuQ5YNdxOpBBpgNdehXau21BJ_)

### Important Things to Remember - GKE

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1czoUFmedUlf8WKFFEEyyhbHOMluZG3_c)

### Scenarios - GKE

![in28minutes slide image](https://drive.google.com/uc?export=view&id=122_XzKXG_SABbUXvsUIgoBbfGRBT47w4)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1aBJIYdFH7t8Dx3beC4DUGgxcH1ztisNv)

### Quick Review - Command Line - gcloud container clusters

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1akq0lK_lnbPb4bF_PS46S7JLqJ_WVaJe)

### Quick Review of GKE & K8s

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1JZZ_h9Y3pDXYcqqqXyOqG91Q9vdCExmr)

## Getting Started with Google Cloud Functions

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1KUy3cL_b00S6IF-JOZ68TBB5NcL9Pshs)

Readings:

- [What is Google Cloud Functions?](https://iromin.medium.com/google-cloud-functions-tutorial-what-is-google-cloud-functions-8796fa07fc7a)

### Cloud Functions - Important Concepts

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11slH4w9NkQIJiszfDjo6kNLfD8L1BF4b)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=19_g-BIXyjbOwEPBlk6Jv5bM6nts831jq)

### Demo - Creating Cloud Functions

- [Cloudera Docs](https://docs.cloudera.com/dataflow/cloud/google-cloud-functions/topics/cdf-create-google-cloud-function.html)

- [Codelabs](https://codelabs.developers.google.com/codelabs/cloud-starting-cloudfunctions#0)

## Getting Started with Google Cloud Run

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1U6L11tTofwkl2xVnyooqWQZzs1-WH1B-)

![Google Developers slide image](https://drive.google.com/uc?export=view&id=1mIWNz2HiAyBEhbRkVOFrGMpjrb_TEikT)

![Google Developers slide image](https://drive.google.com/uc?export=view&id=1nqY4aB-_uGuXWf0qgSdItGA0QJtMF5vN)

![Google Developers slide image](https://drive.google.com/uc?export=view&id=1MLEkt6heEjRkH-0QdPudZ0nE4w1QX--P)

![Google Developers slide image](https://drive.google.com/uc?export=view&id=1I0XsezcS8WsdTIstawSi07TqKXUcD0UR)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1V4r4Xxx51mOKEG12RNgE4ezIukIiAYcU)

Readings:

- [What is Cloud Run?](https://www.bmc.com/blogs/google-cloud-run/)

- [Cloud Run and serverless computing](https://developers.google.com/learn/pathways/cloud-run-serverless-computing)

## Exploring Google Cloud Functions Gen 2

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1giFXP4VEPDTOGA_AF_LqBQ9IAVoNGTzc)

Readings:

- [2nd Generation Google Cloud Function](https://medium.com/geekculture/2nd-generation-google-cloud-function-a069a131e313)

- [Cloud Functions version comparison](https://cloud.google.com/functions/docs/concepts/version-comparison)

### Exploring Cloud Functions - Scaling and Concurrency

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14FsCCeK8eg2Nj2RpS3forEF64nzVYvro)

### Quick Overview of deploying Cloud Functions with GCloud

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1G7zKwytzoRGfv1GRVhnJo8ylkCJWCxUP)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ilj2Aq6Jv0BHywDlD2PJwabo_0DflX14)

## Encryption in Google Cloud with Cloud KMS

### Understanding Data States

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1XUObZx5KGQTw9jsCe6DTpaOlL297UFcU)

### Understanding Encryption - Symmetric and Asymmetric

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1jPwj7VWn8py_lyyz2TE-T-Te5pDfkdHi)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1pwSIsx_azBf4NnA8r1MRkono0zyhb6cp)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=19hNua019mc6GzKiv2mohmDXvlUYdwVPo)

### Getting Started with Cloud KMS

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14HUjvDaQiz3NbCgaORUidUnlLbvOPCrZ)

Readings:

- [Deep Dive Into Google Cloud Key Management Services](https://www.appviewx.com/blogs/deep-dive-into-google-cloud-key-management-services/)

## Block and File Storage in GCP

### Exploring Block and File Storage in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1AoLIsjMYNy1mRugRCGh_ikGKOxeLcdJw)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1mWlR77vw8agX_Nw1N1z4WsXqgQbhnYWW)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1OF-Qm6aEotKGkN7FMHCzi6EGt0ANX8Pq)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ANKhT1ZeN6j9KIzHx2jBKM-vingKb4aW)

Let's quickly see where you can actually look at these options.

So, when we create a virtual machine, that's when you can attach block storage devices with it. You can either attach persistent disks or local SSDs.

During creation of VM, if you go to the boot disk, you will see a persistent disk is attached from where your operating system is loaded and whenever we create a virtual machine, a boot disk is automatically attached with the virtual machine. So by default, a persistent disk called a boot disk is attached with your VM.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1n21mHQUVkZNjzbav-ZPSqIRBqhlzWMLc)

If you'd want to have additional persistent disks attached, then go to Disks > Add New Disk

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1V6rjSKQyNjeOg9-qkpeIjZSaXzbMZZKd)

> Remember, Local SSD is available with selected machine types

Readings:

- [Google Cloud Platform – Filestore](https://www.geeksforgeeks.org/google-cloud-platform-filestore/)

- [Setup Filestore (shared filesystem) on Google Cloud and mount on to Ubuntu systems](https://medium.com/geekculture/setup-filestore-shared-filesystem-on-google-cloud-and-mount-on-to-ubuntu-systems-157fb762b25c)

### Exploring Block Storage in GCP - Local SSDs

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ErVlTDMSpQ62iQ7PXKxk85i0O69KhIGP)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1TWveTAcxg7wacD5oIqr6oqnADUMaZ4F-)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1GawcDKFsEflqsrOFB-BQX4gkX0NCV12k)

### Exploring Block Storage in GCP - Persistent Disks

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1QocI8zjzlGQVd7aqPf4m_ioU0Jz2TjWP)

### Comparing Persistent Disks vs Local SSDs

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1VlpBCZlC6YpgD3TKBkb6SARFMKxBi938)

### Exploring Persistent Disks Types

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1BgTdwPr1Hy-zlkBCs6cncc1Z6Pt96owx)

### Taking Snapshots for Persistent Disks

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1xB5U8JWQs29JixNC01e4cSZxdIkXK3BA)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1g5stACJw_p4AgyzcmHvazXEjGoA1g3ic)

Readings:

- [Google Cloud Compute Engine Snapshots](https://jayendrapatil.com/google-cloud-compute-engine-snapshots/)

### Playing with Persistent Disks and Snapshots

We know that boot disk of persistent disks. However, if you delete your VM, the boot disk will also get deleted. To avoid that you can configure like below:

*While creating the VM*

Go to Boot Disk > Change > Show Advanced Configuration > Deletion Rule > Keep Boot Disk

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1lRRWzIHz098znD___M2lHazwBtgGpLrg)

*In a existing VM*

Go to you instance > Edit > Under Storage (Boot Disk) section > Deletion Rule > Keep Disk

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1yevGZJKcXWGfaok3VNGNCR4giKH2Ljew)

**Creating Snapshot**

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1mvCdcWAuP1aU8CjqXT3TKA5gteNzCRKW)

Once your snapshot is created, you can create an VM instance using it. But remember that snapshots must be created from a boot disk.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1fZMhB5h_AX4SdS39d-whCC8KnylN9peg)

You can also create a disk using snapshot.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1IkhBn7pteLGo2lawrpxmPxAdwMYwP1KF)

**Scheduling Snapshots**

Snapshot schedule is not really linked to a disk. It's a general schedule. Once created, you need to explicitly assigned it to a disk.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1ARizviNp4fPx-y3s2XN7EgGoen_78UB3)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1UVTEgeZUU_KOyfjZim94Cpa4p8wpigy4)

Assigning snapshot schedule to a disk.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1azwHWXUPjX862lEdFQ1L6gwYpd0IyQQA)

### Playing with machine images

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1KBz86UYFRdMFhkTVfxCiR3WWGEcGFOP0)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1hUWX8MYFXXErXnp4Q7v-Scmx-MohUPAz)

After creating a machine image, instance can be created based on it.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1oOUhjUqUDVbYh9PRCmlVCaVt2L7_uYTc)

### Comparing Snapshots vs Images vs Machine Images

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11d7W--AxDd8NOW3eAfmxRGRVcLcWHh__)

### Playing with Disks - GCloud

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1jp9x3Fj-Au3sJBxMwmacFOzHOMBHaj1v)

### Playing with Images - GCloud

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1C4ECYM-7en0n1Iuid91Pg61U19VkJNiq)

### Scenarios - Persistent Disks

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1dkEcUjdSNMKhRjCjjWGqJ6op7vKDZReX)

### Exploring File Storage with FileStore

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1lNFUXjqc8-RsFl4rNMNwWLR1CNjmxGzf)

### Exploring Global, Regional and Zonal Resources

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1dIKfddLRAj8kkNrVVOXZ-S0X8mU0t7Xg)

### Scenarios - Block and File Storage

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1pKV5HZGniLf8RwsUyR0mC4StoWfwq607)

## Object Storage in GCP - Cloud Storage

### Playing with Object Storage in GCP - Cloud Storage

To get an idea about object and cloud storage, we'll start with demo.

Go to search > type Cloud Storage and you might see few buckets like below. Bucket is kind of a container for all the objects that you would want to place in cloud storage. We will talk about it in lengths later.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=14YDWlzhXw0yUAmaQYox-KdkHED7pH2iq)

Let's create a new bucket. For that, click on 'Create Bucket'. Now you have to provide bucket name which must be unique globally. 

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1CEPohAYgJ8bFGoA7Fed0LSQAOB19GgDw)

Next, chose where to store data.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1iKKpVwU2nnVF3TUbnWBTp-0VVvM1DuXP)

Now choose default storage class

![in28minutes demo image](https://drive.google.com/uc?export=view&id=13fkg8eMthB7KRGvnqqjypjocNGfNNNkj)

Let's keep other options with default values.

One of the important things to be noticed in here is that there is no mention of the size of the storage that we would want All that we said is that this is the bucket and this is where we want to create it.

Once bucket is created, you may go ahead and store your data in it.

### Exploring Cloud Storage in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=10ONyZVfOs_ikvgWrT47y59DycCxJ2tLz)

In bucket, objects are stored in key-value pair.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1VXGfpqmMdhCUxk28PZoCFnA1kbVFyNwH)

In below image, '2030/10/course1.png' is the key and value is the content of course1.png image.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1g--yahHr4vBtTnsgiidyhkc4KKkgrisQ)

Whenever we are storing files, we will not be updating files bit by bit. So, whenever we want to change any file, we will create a new image and then upload the entire image as such. So, we would be treating the entire object as a single unit. We'll not do partial updates.

### Understanding Cloud Storage - Objects and Buckets

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1TIYp_nmOPi8xBr9Ae_1pmy1YqmTc8biy)

Readings:

- [Storage Options in Google Cloud Platform - Rundown](https://medium.datadriveninvestor.com/storage-options-in-google-cloud-platform-rundown-f78100c4ed37)

### Understanding Cloud Storage - Storage Classes

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ilVjYRw7mDAZ1iSJEpidKWohI8n-GCQd)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1LkVMLiyUCZkCvdQgbB9cYA0EY78rav_O)

> Storage classes can also be defined at object level. So, in the same bucket, you can have different objects with different storage classes.

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1fHKk4JfN3DyAkpGgEK_bL8e-DynFGMM1)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1rXze5-Bbf-diVjU9m4V0BhOg6iUnigvZ)

### Understanding Cloud Storage - Uploading and Downloading Options

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14RH1MRnjITDYEXjnY1QXimGTZ6L5VcsE)

### Understanding Cloud Storage - Versioning

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Xp4lcjSLnPDMx05IF0Y7RmLvxuO10jJ3)

### Understanding Cloud Storage - Lifecycle Management

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1aj7o54cd0F8pI6WDJG6Og8Z2vMGixSUP)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1XHjRQem7tqFtYjJHNi6sgLTiSUAnkPDt)

To configure the lifecycle for your bucket, go to 'Lifecycle' tab and then 'Add a rule'

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1xrHvCt1zN3A33Yb7LW74p4MM8t0_Lgdn)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=181IV4QM4K5C0G6jHP_Wf3JaCVcJLrcFY)

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1i-B_Ca-eOU3-3aDpuXkWlGjR60keYOZk)

### Understanding Cloud Storage - Encryption with KMS

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1D9p5-El_hu73_ZAEI9yzlQnaZhTR_hH5)

To configure server side encryption, go to 'Configuration' tab of your bucket and click on 'Encryption Type'.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1gjPdLD2_XcQVe_IyK8sZ3GkEWNKRbFlv)

You can also add encryption at the time of creating bucket in 'Advanced Setting' section.

![in28minutes demo image](https://drive.google.com/uc?export=view&id=1du_i2Z4HDBShxBQrZk_JJ4uSJQH7yhvN)

### Scenarios - Cloud Storage

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1mb80M_HYmPW1XXx3EusFHbcr_qXUWbHD)

### Playing with gsutil - Cloud Storage from Command Line

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Nm5PomliiMxHVwg7GOJJ2YYyGTIaRMv8)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1dSnPsTwEoiX7jk4xMs1wREy_BJ8v4qjw)

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

![cloud iam - personal](https://drive.google.com/uc?export=view&id=1ghptb88Ql5DcJWu50xpxIsVTBiK1Tnvo)

**1. Basic Roles**

In filter, type ```Name:roles/viewer``` and you will see more than 2000 permissions are associated with this role. Analyze all such permissions associated with it.

![cloud iam - personal](https://drive.google.com/uc?export=view&id=1XLJOLCsSuXMna0TRMBV9j-ohHP1cOQRF)

**2. Predefined Roles**

In filter, type ```Storage Admin Object``` and you will see more than 10 permissions are associated with this role. Analyze all such permissions associated with it.

![cloud iam - personal](https://drive.google.com/uc?export=view&id=1fXYsxtRvYXXMW_rIKL9cd7MSUKOATCnw)

**3. Custom Roles**

Follow [this link](https://docs.cloudera.com/cdp-private-cloud-base/7.1.3/cloud-data-access/topics/cr-cda-create-custom-role-gcs.html) to know how to create custom roles.

### Exploring Cloud IAM - Members, Role and Policy

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1SCISZSISvZQgdYenqK3qnhQ27yzUvByO)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1UZ-yLCSuvegw21wg58C3akgj155DE1CO)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=18cuIiKBar_pXS5LHzKFdw6E7QbNtaGvG)

### Demo - Playing with IAM (DIY)

<ins><strong>GUI</strong></ins>

Below things are covered in this demo:

- In search bar, type **IAM** and try adding a new member, modify present member roles.

- Checkout **Policy Troubleshooter**.

<ins><strong>CLI</strong></ins>

Below are few important commands used to perform IAM related tasks:

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1VY7A-_gJXy9UPsaeAUMF7SUUeGRe0IXD)

### Getting started with Service Accounts

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1DGu_tCWGA5QCvd-lpJY6PY_FKDkzwuKv)

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

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ZSpmfT7us3eBI2RjED_Up82pVty4ksUB)

**Use Case 2 - Connect on premises machine to cloud storage**

Until now, we have been talking about resources which are present in Google Cloud. Now, let's suppose there is a server present outside GCP.

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1vDy0BiWXtj5hIgWS0_LrcoiSmHE8sd6x)

**Use Case 3 - Connect on premises machine to cloud storage but for few hours**

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Dc8VSUGqPHclGrTyMRAcJ5ubYhFJOwJM)

### Scenarios - Service Accounts

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11NKGyfdltR2KUntIdCmt2uPmvt-1MCHY)

### ACL(Access Control Lists) - Part of Cloud Storage

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1L96tUiDtcr5kivWg9Uni8yse484FN8KM)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14JL3c-63eskJEf7cBw4k6Sfj07Myu34g)

Readings:

- [Access control lists (ACLs) - Official Docs](https://cloud.google.com/storage/docs/access-control/lists)

### Signed URLs - Part of Cloud Storage

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1wjW7xtp_uQxYz14uCQdrY3CmkoOZSTwy)

Readings:

- [Signed URLs - Official Docs](https://cloud.google.com/storage/docs/access-control/signed-urls)

### Exposing a Public Website using Cloud Storage

Suppose, you want to expose buckets, let's say, in a public website, then below are the steps to do so:

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1FJN37hOR0Do6FEQRADwZm2YVnHKJls3S)

Readings:

- [Make Data Public - Official Docs](https://cloud.google.com/storage/docs/access-control/making-data-public)

## Choosing Database in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1dVBA2YDD9xc6c8JVB7PYZM0XiEuQ2TOJ)

### Understanding Database Fundamentals - Snapshot, Standby etc

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1qJEWFrfYN6opIKInzaHFAYqvYs2p0v92)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1eUNbDbV31_QGV745BAwBF-VSs4Pq4kyH)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1kep6c6Vfi3f74vsY9_o0KqDzHqnavkHL)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1NUR4q8pbAEtM_sQNvqNUlbPnxobS04fi)

Readings:

- [The Transaction Log](https://learn.microsoft.com/en-us/sql/relational-databases/logs/the-transaction-log-sql-server?view=sql-server-ver16)

### Understanding Database Fundamentals - Availability and Durability

![in28minutes slide image](https://drive.google.com/uc?export=view&id=197K_Az3-Z1ZoelzDtgh0a4AWMnOsTSaS)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1qF4sF7czzpF3_82QDqLEvu-rruCyxRzC)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1T1OE9FRResud6vxkDP6GnszGdopjwayU)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1WNXyUgLE0nSQ0DFBbvU3sjYTh4b0Dps_)

### Understanding Database Fundamentals - RTO and RPO

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1lr76uuy_t1qxN4RqRHDZI_XjbibI8Wlz)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=12Oej_hupfAtEWcWRBqUAusCfdvJ7C3ns)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1dBIWuBQDswhFXDmElXrHYBTpui4x_1aK)

### Understanding Database Fundamentals - Read Replicas

![in28minutes slide image](https://drive.google.com/uc?export=view&id=15IVDSaknHLFnDsMNSTmFcioN2t8v49sU)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Ce5Npg4lFB3dqmNXddxx6bmMhQt6elQv)

### Understanding Database Fundamentals - Data Consistency

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1aafEqJcyBQQcNHKAds3lInD9cEwtvB05)

### Understanding Database Fundamentals - Choosing Databases

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1w8B_9wC5UoZv8hnVJhVWgsSsENIpBHuO)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1tbfffJF-NB-gXjBJatmpdfMHiyvhI3zc)

### OLTP Relational Databases in Google Cloud - Cloud SQL and Cloud Spanner

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1J2ixTHXkSnQQcy04M-S6j7mDu_3kCPng)

### OLAP Relational Databases in Google Cloud - BigQuery

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1LsbJxZ20CfCT0n8CJDpUTfZN7QQ0ikoL)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1sNVm2KrDSBBkDoVHbIAQ5f1Gf1m4C5xP)

### NoSQL Databases in Google Cloud - Firestone, Datastore and BigTable

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Bk91sFiYWPPpjN0Sy9T55tORzIrvUsdL)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1u6VR8Iu41Ah3Ap6D5fCVkccz8Pc9f7cg)

Readings:

- [NOSQL DATABASE SERVICES](https://datavalley.technology/nosql-database-services-cloud-datastore-cloud-firestore-and-cloud-bigtable/)

### In Memory Database in Google Cloud - Memorystore

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1YFqPsVbWPqHmStTiZbGVSVmxC-TLB_65)

### Databases in Google Cloud Platform - A Quick Review

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1og7h0JhPAenA-xKJT0HXQKxLfg0ghqLp)

### Databases in Google Cloud Platform - Scenarios

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1HRXT6iWucLRaZnhKoTW4C67fiaYNqFca)

## Exploring Databases in Google Cloud Platform

### Getting Started with Cloud SQL

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Ui8aPYGIJY46qG0No1JKuMUmYs10h38b)

### Demo - Playing with CloudSQL

- To begin with Cloud SQL, in search bar, type Cloud SQL and select SQL

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1wtGOqzkHenGguSvv3Vk82qrQ2_daNY4q)

- Click on create instance, select the database provider, configure it and create the instance.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1MMu-7Wp6ShlnbDwYEjIN9S2OStfeSqwH)

- Once your instance is up, create the database.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1Hg_keRJQkCMgT580tA0wC6FtkXycRInd)

- To interact with database (performing database related operations like creating tables etc), go to Overview > Connect using Cloud Shell

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1PVzR7DM-8YOfJBSYyrnJ5WTnLvP_snPZ)

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1CTZCNM6rW_QgSLvaIYsHBVipTlrlzQnm)

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

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1kf-Uji3KIMyboEJcRjSyxy92cu-ThPRQ)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1YzGuwBHJeZFEH8bRlamOxVbm37MJkptT)

### Getting Started with Cloud Spanner

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1pghji2xDZECV-W_B8ify2gERQ102jIjS)

### Demo - Playing with Cloud Spanner

- Search Bar > Cloud Spanner > Create Instance

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1weRB4Ls7Ex4c6crJN9MDXwlJCyTlIUye)

- Configure it as per your requirements.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=16-iILfYOxaEYcAdJL460ol_oahaFXSbg)

- In 'Allocate Compute Capacity', you can either choose 'node' or 'processing unit' (it is introduced recently).

- Once cloud spanner instance is created, proceed with the database and table creation.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1J0HJQluaN5m3nEIDgiiiK_8jTIQRzp5t)

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1RH1qAqAQuK0Bgjde0F6DCD3cGnHVoH_r)

    ```
    # Cloud Spanner
    CREATE TABLE Users (
    UserId   INT64 NOT NULL,
    UserName  STRING(1024)
    ) PRIMARY KEY(UserId);
    ```

### Getting Started with Cloud Datastore and Cloud Firestore

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11--dFiSiyCpHgqxZGF0JEA8ccPIbqQU1)

### Demo - Playing with Firestore

- Search Bar > Firestore > Select desired mode. Cloud Firestore is the next generation of cloud Datastore. So, if you're creating new projects then the recommendation is to go for Native mode. However, if you have old Datastore projects that you are moving over to Firestore then the recommendation is to go with Datastore mode. ***Remember, once you choose the mode, it will be permanent for your project.***

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1Zr7VFyT6HcJzI2aZAhr5RTTvxDE1X8X7)

- Once mode is chosen, select the location, which can be regional or multi-regional.

- After doing all above and click on 'create database' to create the database.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1QglIysrGkeZyypcmZTHTHeyjz79XjesD)

- Now, to add data into the database, click on 'start collection'. A collection is a set of one or more documents that contain data. It is similar to tables in relational database. Once collection is created, to store data, you have to create document under which you can define your fields.

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1uz1wEHNkg39DVXExZMyCAnm4Xho3UY5O)

- One of the important things to remember about Datastore or Firestore is the fact that it is hierarchical. It means inside a document, you can add another collection.

### Getting Started with Cloud BigTable

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11jzmDFugtNotDM35r4f0eZ875XVp6GmV)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1B7K93zuUSFofHm1gQtFUS7hIwCFSWRwQ)

### Getting Started with Memorystore

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1sdfyxGrvBkeXsF7Aeh5VuFh6i98r1UPN)

### Demo - Playing with Memorystore

- Search Bar > Memorystore > Create Instance (for redis or memcached, based on your requirements)

    ![in28minutes demo image](https://drive.google.com/uc?export=view&id=1VB6FdGuGpUyAXHc7iCFOHfhM9x90cl4v)

- Provide configuration details and click on create.

### Getting Started with BigQuery

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1kQzwVxtjyYC507rjplWpi6jOlqpnxlRm)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1zJPqClKvmP4JmhaIXvU-A2ehBO2Wm7Rb)

### Playing with Cloud SQL, BigQuery and Big Table from Command Line

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Rhz6kdP4mk-WY2Jymyhn-DjuzVmnJ9Jb)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14_iPob-UbOitnRogeBNSWZPZKrHVZ0dL)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Lzd1cOpGIaclGjl84HRTH3u-dcxikOtH)

### Importing and Exporting Relational Databases

Whenever you look at any of the import or export scenarios in Google Cloud platform, you would see that typically cloud storage is involved. Whenever you'd want to move data from somewhere to somewhere, you would first move it to cloud storage and then move it to the destination and that's the reason why you would see that most of these services support export to and from cloud storage.

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1A786Cccw3zvy_A_LbyuPMQfdvuysulpg)

### Importing and Exporting NoSQL Databases

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1s7bed5OgKd-z9LQkDJgr_ClkV98ExAo2)

### Databases in Google Cloud Platform - Summary

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1QVhDZGjntUXTuxk_Ta7Q7ICZd_GA4JfO)

## Asynchronous Communication in Google Cloud with Cloud Pub Sub

### Understanding the need for Asynchronous Communication

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1RfkyYH6z9jtAZdXC45RkakRK0XiStz1q)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1TM119xS8rNh9xfn0vFr8_fGo_bdYo3h8)

Readings:

- [Asynchronous Communication — Methods and Strategies](https://dzone.com/articles/asynchronous-communication-methods-and-strategies#:~:text=The%20biggest%20benefit%20of%20asynchronous,also%20lead%20to%20better%20scalability.)
- [Understanding Synchronous and Asynchronous Communication](https://www.microfocus.com/documentation/silk-performer/205/en/silkperformer-205-webhelp-en/GUID-6CC17B5B-71B7-4703-B9E6-C81835A5335A.html)

### Getting Started with Cloud Pub Sub

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1AgHJkvdmxb5JtEChZYIAW6lkIDe4EGyo)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1TbD90kqhchaffUlLqpiZ7nuJucGmfTuv)

Readings:

- [What is Pub/Sub?](https://cloud.google.com/pubsub/docs/overview)
- [Google Cloud Pub/Sub – Asynchronous Messaging Service](https://k21academy.com/google-cloud/google-cloud-pub-sub/)

### Exploring Cloud Pub Sub - Publishing and Consuming a Message

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1KJpDgxUX2b1no_edmCUExU9RRt_8DH6C)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=16Eyzxwfd3ugyc-EC4a2HmN0AwexaSt5N)

### Demo - Playing with Pub/Sub

**[Pub/Sub Demo](https://www.youtube.com/watch?v=f5DOsB7Nlw0&list=PLIivdWyY5sqKwVLe4BLJ-vlh9r9zCdOse&index=3)**

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1RlZ1gS8hCphjOlWT2D_wKBpdji_ou9Ju)

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

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1QEL1_4X2qFyZCeHdT4gROGEGDLbIv4x8)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Y5Z0LnJvDIJ6md0QeaExdB_Dq2t5nb0f)

Readings:

- [Google Cloud VPC (Virtual Private Cloud) for Beginners - K21Academy](https://k21academy.com/google-cloud/google-cloud-vpc/)

### Understanding the need for VPC subnets

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1RmCTgGP7tY3tsoxaVDyYPgQ3QnTOq2Kt)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1OOwBr-JjnhF1ooz5fMfLhWeXrGdE254J)

Readings:

- [Subnet Mask - Explained (YouTube)](https://www.youtube.com/watch?v=s_Ntt6eTn94)
- [Subnetting in Networking | Subnetting Examples](https://www.gatevidyalay.com/subnetting-ip-subnetting-examples/)

### Creating VPCs and Subnets in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1JDKYncknJP49Sn0PMYlsoRj2D6QlUGY1)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1kg0UAN7fA3Yj27gIvvvBuSoQ-YISlpJZ)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1oK2QunuqhvVlcgAgH6hEn0mmQVMT3ivM)

Follow below links to see the creation of VPCs in GCP

- [How to Create VPC (Virtual Private Cloud) Network in GCP - linuxtechi](https://www.linuxtechi.com/create-vpc-network-in-gcp-google-cloud/)
- [VPC Creation on Google Cloud Platform(GCP) - Medium](https://medium.com/petabytz/vpc-creation-on-google-cloud-platform-gcp-67fa397c1106)

Readings:

- [CIDR Range Visualizer](https://cidr.xyz/)

### Understanding Firewall Rules in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1gbPKbuivgql40BUJ7z3e_BRgdxjS-ehz)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1mxDdYlHf3jGuN-GPCrL_fh83zVW7Ee9H)

### Getting Started with Shared VPC

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1nZ01koPIjY1fwHj-cHM_nuNpcDRz27m0)

### Getting Started with VPC Peering

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Cj4VENT8aWEFp0Du7vgPlkG3cKr1nBOw)

### Implementing Hybrid Cloud with Cloud VPN and Cloud Interconnect

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1RRjyf8DDv9ZtUOwN_77YCd0ewPw2mJcw)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1aJteByW3x1bk2J34hjhSdXTgp0LvGCvQ)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1cxxR6sxmbs2j5fCBVGCsULVdiaAquQVn)

Readings:

- [Configuring a Shared VPC on GCP - VMware Tanzu Docs](https://docs.pivotal.io/ops-manager/2-10/install/gcp-shared-vpc.html)

## Operations in Google Cloud Platform

In this section, let's look at how you can perform operations in the cloud. Developing applications is important.
However, maintaining applications and maintaining them in production is very important as well. That's where monitoring, logging, tracing, debugging, and all these kind of things become really, really important.

### Getting Started with Google Cloud Monitoring

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1wDjr6VfftmdV-frsm_hWgaQd7FmiklcG)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1VFCKJOVhP4KAHlKgbYB1P4Rgvx0equOa)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11RXsOnMVbk41xQqOp-E9VxTvcCUDPXQD)

Readings:

- [Getting started with Cloud Monitoring](https://www.youtube.com/watch?v=wY8cmFY4ua8)

### Getting Started with Google Cloud Logging

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1xMYFzlGL3sbvVkUeQV6bM83gL_CDcxrz)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=10dZMEKwcbpCL2aGrajwkF9DA3hL1tuZ2)

### Exploring Google Cloud Logging - Audit Logs

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1toZCzo6TVarH0rTNkjhsU1ykWS-SAntz)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1okjrG1UQu_KK8J4CtNTDOA0QUFgRVK09)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1j0NI1vRn8vHAf2x05feLpEYzWClDGo6U)

### Exploring Google Cloud Logging - Routing Logs and Exports

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1gF_UQykf5dTCL1jmpS62HsmsWSRIR1sM)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=16GXHOZRmD_ABBKad1jVhRqxVZrJB8t6v)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1O7dTMg4IbPUF1-6UPlpFbIDx9G-5BwMl)

Readings:

- [Understand your services with Cloud Logging](https://www.youtube.com/watch?v=IlUCyV8mcS0)

### Creating a Cloud Storage Bucket and Cloud Function

This is a practice section where you need to create a bucket and then associate a cloud function to it which will be triggered as soon as any object is uploaded to this bucket. In this cloud function you can do implement anything which generates a log when an object is uploaded to bucket.

The whole purpose of this exercise is to demonstrate the cloud logging.

### Getting Started with Google Cloud Trace

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1KfhnActw7FHRW46Ej2AGKsb25gzOP7dl)

Readings:

- [Cloud Trace - GCP](https://cloud.google.com/trace#:~:text=Cloud%20Trace%20is%20a%20distributed,near%20real%2Dtime%20performance%20insights.)

### Getting Started with Google Cloud Debugger

![in28minutes slide image](https://drive.google.com/uc?export=view&id=13Yh93MpTWyX6Zoxdswn8Bu1Txz6qylhp)

### Cloud Profiler and Error Reporting

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1V9R7xhckSyr8hVUqWwQtJh1wGdDOJrlN)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1HVIaEfK9VQmzmRdMBuBoEN_f7V8wag_v)

### Scenarios - Operations in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1GeGd-b_iI9SgzxGk-DpndSmKkWjoNOux)

## Organizations and IAM - Organizing Google Cloud Resources

### Organizing Google Cloud Resources - Projects, Folders and Organization

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1hfB9lZGanDOVESFIZXxxk3hbzw0NkrEo)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1mSIY9TR91Cu7f4-B-c_yxHaJshvrSGRG)

> Note
>
> In a free tier, we don't have organization and folders. We directly create projects.

Readings:

- [Resource hierarchy - Official Docs](https://cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy)

### Exploring Billing Accounts

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1BCHl72VgN6nJpvQN97oAELhyObSqi8Wx)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Q2OEj0SckqeUb6mJiM5iQfJiYdSLSOtQ)

### Understanding IAM Best Practice

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1UuzZno0VUY2_Klc0T7QfR-lk1lAFee4o)

### Understanding User Identity Management in GCP

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1gsZgKUKCOqWaNPubqLe8z1jaV96dqE6n)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=15E5sXVIaCQFL0CfQyJ7iOd4Qb-VDMnAt)

### Exploring IAM Members and Identities

Let's look at different types of IAM Members or Identities:

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1AoY3EJG8DihoO3KiDd-DvrM5xsh3uJsC)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1ulpI1kqmjxTWmNCof_7FGpv23KpGVy0c)

Readings:

- [Overview of Cloud Identity](https://cloud.google.com/identity/docs/overview)
- [Single Sign-on vs. Federated Identity Management](https://www.pingidentity.com/en/resources/blog/post/sso-vs-federated-identity-management.html#:~:text=Federated%20identity%20management%2C%20also%20known,and%20authenticate%20users%20across%20domains.)

### Understanding Organization Policy Service

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1J11RmvfJKFFsiH68ofhSKJlwwvPmRSlL)

> Note
>
> Organization policy always overrides whatever is configured in IAM. So, if an organization policy prohibits the creation of resources in, let's say, a specific region even though a user might have that access through IAM, he will not able to create the resource in that specific region because Organization policy has the highest priority.

### Exploring IAM policy at multiple levels - Resource Hierarchy

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1WKEiIvaltGfs1V1iUBPhj0bgzWtYqE7v)

Readings:

- [What is Identity and Access Management in Google Cloud?](https://www.educative.io/answers/what-is-identity-and-access-management-in-google-cloud)

### Exploring IAM Predefined Roles - Organization, Billing and Project

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1a7Pe45Z11yhoE38OQ6JxU9iDiCxvJeW5)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Xn-kn1q2-0A4v4zsf1ZCtX90-9y0XRR9)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1xV6AKgPWCyONnxp6r1nWF8yACgH_zfDh)

### Exploring IAM Predefined Roles - Google Compute Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1DcfDfE2iRAmDGgZtcsbgBtGkIBrJmRe2)

### Exploring IAM Predefined Roles - Google App Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1LyMaLyYCYViGcz0Tij7M9rJJDBLTAOxB)

### Exploring IAM Predefined Roles - Scenarios

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1xnON9GUykhQh6jWoxwKlmzvp0ir_yz6M)

### Exploring IAM Predefined Roles - Google Kubernetes Engine

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1P8pce-D3LmNAGoZjYEIKrz9A_xSFgInr)

### Exploring IAM Predefined Roles - Google Cloud Storage

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1WhLqD2OWR_XV_lrhVgpri_GudtQ_LVBK)

### Exploring IAM Predefined Roles - Google Cloud BigQuery

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1-iz03ohpskXlUNA6YZDFyD4WWQE_RnPK)

### Exploring IAM Predefined Roles - Logging Service Accounts

![in28minutes slide image](https://drive.google.com/uc?export=view&id=14M-Qi_sb731esgNIVoz7DB5gigsg-BBl)

### Other Important IAM Roles

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1fWULgszOkUaL3CR8OAsEEIVAYJnRFhs1)

### SSHing into Linux VMs

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1k-PP47KTLkyFO70GWtQwtJJKw5qBVkcB)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1NLhcctVJWAw-jD2l-fQ5v5o-SLcL_4zt)

### Exploring IAM Scenarios

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1_m3VJW30Qv71690p_dzPh-HEAGQ1umMd)

## Exploring Google Cloud Platform - GCP - Pricing Calculator

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1Jnh35mT4BBGmbXgjzsngK2tzzAc72EUl)

Click here to access [Google Price Calculator](https://cloud.google.com/products/calculator).

## Google Cloud Platform - Other Important Services

### Getting Started with Cloud Deployment Manager

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1NDw4YUsvqd_skV2o22idYxsLRDhmJw-v)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1yl6we-EULuOqa972cptLIhulsHi9MUQP)

### Understanding Cloud Deployment Manager

![in28minutes slide image](https://drive.google.com/uc?export=view&id=11uhOg2I3zJ7aODfSXlFJIucXWv-NfmyI)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1GBq2Y7EKkUbwOqDv52fqnvj4nYd8IydE)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1v8Ie7AnppJqxVm-x6pFVScUl25TnT7P1)

### Getting Started with Cloud Marketplace

![in28minutes slide image](https://drive.google.com/uc?export=view&id=152fdO9aHJCMVhAvyeweVdwiTv5ESshfx)

### Getting Started with Cloud DNS

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1H7LgcnkVDUJ--AWuVdAqLjLTElpA1vTM)

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1NacOm6vNbVfS_z24PosaRVxlg4mLL_El)

### Getting Started with Cloud Dataflow

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1nyzrNDrY9AttC243kusw3Ve8bGkYH2xC)

Readings:

- [Google Cloud Dataflow](https://www.zuar.com/blog/what-is-google-cloud-dataflow/)

### Getting Started with Cloud Dataproc

![in28minutes slide image](https://drive.google.com/uc?export=view&id=1d2WO-E4c_5GXjrRbSidFdIqBpace_ehG)

Readings:

- [What is Dataproc?](https://cloud.google.com/dataproc/docs/concepts/overview#:~:text=Dataproc%20is%20a%20managed%20Spark,you%20don't%20need%20them.)

## References

- [GCP Associate Cloud Engineer - Google Cloud Certification - in28Minutes Official, Ranga Karanam | GCP Certification - Google Cloud Engineer & Architect](https://www.udemy.com/course/google-cloud-certification-associate-cloud-engineer/)