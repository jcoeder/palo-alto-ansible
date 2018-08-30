# palo-alto-ansible

Working on something to upgrade active/passive clusters.

Update inventory.ini to your represent your hosts

edit update-a.yml and update-b.yml to the version of code you wish to deploy

update-cluster.yml uses vars for code version



### YOUR FIREWALLS MUST HAVE PROPERLY CONFIGURED SERVICE ROUTES, WORKING DNS, AND CURRENT LICENSING





# Other Configuration Items

CentOS7 and Redhat7 now ship with Python 2.7.5 or later.  By default SSL certification validation is enabled.  Disable this to make your life easier.

/etc/python/cert-verification.cfg

verify=disable


As of August 2018 Fedora still uses python 2.7.15.  No need to make the above changes.
