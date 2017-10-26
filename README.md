# ansible-tomcat

## Introduction

The scope of this playbook is to Install and Setup Tomcat V-8.X.X on Centos/7.

``` "Do a cat on group_vars/tomcat"
This is the Variables File we Declare the required metadata
```

``` "Take a look Roles"
notice that roles have 2 folders but for the purpose of this play book the site.yml invokes only the tomcat8 role as for this Playbook we are installing jdk-1.8 from yum rather than from Oracle.
```
## Prerequisites

### Step 1
Have you configured a ssh keypair across you master and hosts for a user with sudo on nodes where this playbook will run?


### Step 2
Have you modified the site.yml in present working dir to perform as a specific user and to which environments (hosts) to run the playbook?

### Step 3
```shell "this will dry run your playbook against the Hosts for Syntax checking"
ansible-playbook site.yml -C 
```
