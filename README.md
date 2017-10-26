ansible-tomcat
===============
#
##Prequisites
-------------
M^-
#Step 1
Have you configured a ssh keypair across you master and hosts for a user with sudo on nodes where this playbook will run?
M^
#Step 2
Have you modified the site.yml in present working dir to perform as a specific user and to which environments (hosts) to run the playbook?
M^

### ansibleインストール

```shell
sudo yum install -y epel-release
