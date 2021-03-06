---
title: Getting Started
menu:
  enterprise_1_0:
    weight: 20
    parent: Introduction
---

Now that you successfully [installed and set up](/enterprise/v1.0/introduction/installation/) InfluxEnterprise, visit
`http://<your_web_console_server's_IP_address>:3000` to get started with the
web console!

When you first visit the web console, it prompts you to:

#### 1. Name your cluster

The first step is to name the cluster that you setup in the
[previous document](/enterprise/v1.0/introduction/installation/).
Here, we call our cluster `MyCluster`.

![Name your cluster](/img/enterprise/name_cluster_1.png)

#### 2. Create a Cluster Admin account

Next, create a Cluster Admin account.
The Cluster Admin account has all [cluster-specific permissions](/enterprise/v1.0/features/users/#permissions).

We recommend calling this account `ClusterAdmin`.
Note that you will need to authenticate with the `ClusterAdmin` username and
password if you're interacting with your InfluxEnterprise cluster [outside](https://docs.influxdata.com/influxdb/v1.0/tools/) of the
web console.

![Create Cluster Admin](/img/enterprise/create_cluster_admin_1.png)

#### 3. Create a Web Admin user

The final step is to create a Web Admin user.
The Web Admin user has all [web-console-specific permissions](/enterprise/v1.0/features/users/#admin-users).

After filling out the form with your name, email, and password, be sure to
assign yourself to the `ClusterAdmin` account that you created in the previous
step.
This ensures that you have all web console permissions AND all cluster-specific
permissions.

![Create Web Admin](/img/enterprise/create_web_admin_1.png)
