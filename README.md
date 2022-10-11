# GCP - Associate Cloud Engineer

## Contents

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

- [References](#references)

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

![cloud iam - personal](other/images/Cloud_IAM/1_cloud_iam.png)

**1. Basic Roles**

In filter, type ```Name:roles/viewer``` and you will see more than 2000 permissions are associated with this role. Analyze all such permissions associated with it.

![cloud iam - personal](other/images/Cloud_IAM/2_cloud_iam.png)

**2. Predefined Roles**

In filter, type ```Storage Admin Object``` and you will see more than 10 permissions are associated with this role. Analyze all such permissions associated with it.

![cloud iam - personal](other/images/Cloud_IAM/3_cloud_iam.png)

**3. Custom Roles**

Follow [this link](https://docs.cloudera.com/cdp-private-cloud-base/7.1.3/cloud-data-access/topics/cr-cda-create-custom-role-gcs.html) to know how to create custom roles.

### Exploring Cloud IAM - Members, Role and Policy

![in28minutes slide image](other/images/Cloud_IAM/4_cloud_iam.png)

![in28minutes slide image](other/images/Cloud_IAM/5_cloud_iam.png)

![in28minutes slide image](other/images/Cloud_IAM/6_cloud_iam.png)

### Demo - Playing with IAM (DIY)

<ins><strong>GUI</strong></ins>

Below things are covered in this demo:

- In search bar, type **IAM** and try adding a new member, modify present member roles.

- Checkout **Policy Troubleshooter**.

<ins><strong>CLI</strong></ins>

Below are few important commands used to perform IAM related tasks:

![in28minutes slide image](other/images/Cloud_IAM/7_cloud_iam.png)

### Getting started with Service Accounts

![in28minutes slide image](other/images/Cloud_IAM/8_cloud_iam.png)

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

![in28minutes slide image](other/images/Cloud_IAM/9_cloud_iam.png)

**Use Case 2 - Connect on premises machine to cloud storage**

Until now, we have been talking about resources which are present in Google Cloud. Now, let's suppose there is a server present outside GCP.

![in28minutes slide image](other/images/Cloud_IAM/10_cloud_iam.png)

**Use Case 3 - Connect on premises machine to cloud storage but for few hours**

![in28minutes slide image](other/images/Cloud_IAM/11_cloud_iam.png)

### Scenarios - Service Accounts

![in28minutes slide image](other/images/Cloud_IAM/12_cloud_iam.png)

### ACL(Access Control Lists) - Part of Cloud Storage

![in28minutes slide image](other/images/Cloud_IAM/13_cloud_iam.png)

![in28minutes slide image](other/images/Cloud_IAM/14_cloud_iam.png)

Readings:

- [Access control lists (ACLs) - Official Docs](https://cloud.google.com/storage/docs/access-control/lists)

### Signed URLs - Part of Cloud Storage

![in28minutes slide image](other/images/Cloud_IAM/15_cloud_iam.png)

Readings:

- [Signed URLs - Official Docs](https://cloud.google.com/storage/docs/access-control/signed-urls)

### Exposing a Public Website using Cloud Storage

Suppose, you want to expose buckets, let's say, in a public website, then below are the steps to do so:

![in28minutes slide image](other/images/Cloud_IAM/16_cloud_iam.png)

Readings:

- [Make Data Public - Official Docs](https://cloud.google.com/storage/docs/access-control/making-data-public)

## Organizations and IAM - Organizing Google Cloud Resources

### Organizing Google Cloud Resources - Projects, Folders and Organization

![in28minutes slide image](other/images/organisation_and_iam/1_organisation_and_iam.png)

![in28minutes slide image](other/images/organisation_and_iam/2_organisation_and_iam.png)

> Note
>
> In a free tier, we don't have organization and folders. We directly create projects.

Readings:

- [Resource hierarchy - Official Docs](https://cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy)

### Exploring Billing Accounts

![in28minutes slide image](other/images/organisation_and_iam/3_organisation_and_iam.png)

![in28minutes slide image](other/images/organisation_and_iam/4_organisation_and_iam.png)

### Understanding IAM Best Practice

![in28minutes slide image](other/images/organisation_and_iam/5_organisation_and_iam.png)

### Understanding User Identity Management in GCP

![in28minutes slide image](other/images/organisation_and_iam/6_organisation_and_iam.png)

![in28minutes slide image](other/images/organisation_and_iam/7_organisation_and_iam.png)

### Exploring IAM Members and Identities

Let's look at different types of IAM Members or Identities:

![in28minutes slide image](other/images/organisation_and_iam/8_organisation_and_iam.png)

![in28minutes slide image](other/images/organisation_and_iam/9_organisation_and_iam.png)

Readings:

- [Overview of Cloud Identity](https://cloud.google.com/identity/docs/overview)
- [Single Sign-on vs. Federated Identity Management](https://www.pingidentity.com/en/resources/blog/post/sso-vs-federated-identity-management.html#:~:text=Federated%20identity%20management%2C%20also%20known,and%20authenticate%20users%20across%20domains.)

### Understanding Organization Policy Service

![in28minutes slide image](other/images/organisation_and_iam/10_organisation_and_iam.png)

> Note
>
> Organization policy always overrides whatever is configured in IAM. So, if an organization policy prohibits the creation of resources in, let's say, a specific region even though a user might have that access through IAM, he will not able to create the resource in that specific region because Organization policy has the highest priority.

### Exploring IAM policy at multiple levels - Resource Hierarchy

![in28minutes slide image](other/images/organisation_and_iam/11_organisation_and_iam.png)

Readings:

- [What is Identity and Access Management in Google Cloud?](https://www.educative.io/answers/what-is-identity-and-access-management-in-google-cloud)

### Exploring IAM Predefined Roles - Organization, Billing and Project

![in28minutes slide image](other/images/organisation_and_iam/12_organisation_and_iam.png)

![in28minutes slide image](other/images/organisation_and_iam/13_organisation_and_iam.png)

![in28minutes slide image](other/images/organisation_and_iam/14_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Compute Engine

![in28minutes slide image](other/images/organisation_and_iam/15_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google App Engine

![in28minutes slide image](other/images/organisation_and_iam/16_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Scenarios

![in28minutes slide image](other/images/organisation_and_iam/17_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Kubernetes Engine

![in28minutes slide image](other/images/organisation_and_iam/18_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Cloud Storage

![in28minutes slide image](other/images/organisation_and_iam/19_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Google Cloud BigQuery

![in28minutes slide image](other/images/organisation_and_iam/20_organisation_and_iam.png)

### Exploring IAM Predefined Roles - Logging Service Accounts

![in28minutes slide image](other/images/organisation_and_iam/21_organisation_and_iam.png)

### Other Important IAM Roles

![in28minutes slide image](other/images/organisation_and_iam/22_organisation_and_iam.png)

### SSHing into Linux VMs

![in28minutes slide image](other/images/organisation_and_iam/23_organisation_and_iam.png)

![in28minutes slide image](other/images/organisation_and_iam/24_organisation_and_iam.png)

### Exploring IAM Scenarios

![in28minutes slide image](other/images/organisation_and_iam/25_organisation_and_iam.png)

## References

- [GCP Associate Cloud Engineer - Google Cloud Certification -  in28Minutes Official, Ranga Karanam | GCP Certification - Google Cloud Engineer & Architect](https://www.udemy.com/course/google-cloud-certification-associate-cloud-engineer/)