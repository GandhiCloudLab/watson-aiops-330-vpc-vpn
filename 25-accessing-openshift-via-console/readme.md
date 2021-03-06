# Accessing OpenShift via Console

This document explains about how to access OpenShift installed in VPC via Console 

## 1. Create new profile in Firefox profile

This is one time process. You can skip if it is already done.

Refer [../22-create-new-profile-in-firefox](../22-create-new-profile-in-firefox)

## 2. Create ssh proxy to the strongSwan in Virtual Server

Refer [../23-create-ssh-proxy-to-virtual-server](../23-create-ssh-proxy-to-virtual-server)

## 3. Access OpenShift Console

1. Enter `about:profiles` in the address bar of the Firefox browser.

<img src="images/image-00001.png">

About Profile page opens.

Already created profile is available in the bottom of the page.

2. Click `Launch profile in new browser`

<img src="images/image-00005.png">

3. Enter the `Private URL of the Openshift`

<img src="images/image-00009.png">

4. After the login and all you can see the Openshift console page.

<img src="images/image-00010.png">


## References

This document is based on https://pages.github.ibm.com/hdm-swat/guides/vpn-secured-cluster/
