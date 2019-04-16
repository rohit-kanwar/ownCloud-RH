# ownCloud Server Quick Start Guide

ownCloud is the open platform for more productivity and security in digital collaboration. ownCloud is secure enterprise file sharing. ownCloud is hosted in users data center offering unsurpassed transparency, security and control and can be flexibly integrated into the existing environment.

Also users can access company files quickly and easily from anywhere and from any device. This increases both safety and productivity.

## CHAPTER 1. SHOULD YOU USE THIS GUIDE?

Are you administrator or user? We got it all covered here. Chapter 2-5 are for administrators and 6 is for user.

This guide gives an overview for the installation , configuration, and user setup for ownCloud server. 

## CHAPTER 2. DOWNLOADING OWNCLOUD SERVER IMAGE

Visit https://owncloud.com/download/ and in the section Download ownCloud Server click __DOWNLOAD__. Fill in your details and choose version  and then click __DOWNLOAD OWNCLOUD__.

![image](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C2%20ownCloud%20Server%20Download.png)

It can take considerable time, depending on available bandwidth.

## CHAPTER 3. VIRTUALBOX INSTALLATION

Before we install ownCloud server a virtual machine is required for virtual environment. Skip the following steps if VirtualBox is already installed.

1. Click __Next__.

![Virtual Box](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/Virtual%20Box.png)

2. In the __Custom Setup__ window click __Next__.

![Custom Setup](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C3-2Custom%20%20Setup%2002.png)

3. In the next __Custom Setup__ window click __Next__.

![Custom Setup](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C3-3%20Custom%20%20Setup%2003.png)

:warning: By clicking __Yes__ you will be disconnected temporarily from network.

4. Click __Yes__.

![Permission](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C3%20-04%20Warning%2004.png)

5. Click __Install__.

![Install](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C3%20-5Install%2005.png)

6. Click __Finish__.

![Finish](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/Installation%20C3-6%20Complete%2006.png)

Installation of VirtualBox is now complete.

## CHAPTER 4. INSTALLING UNIVENTION-APP-OWNCLOUD-VIRTUALBOX IN VIRTUALBOX

1. Double click __Oracle VM VirtualBox__ icon if it does not start.
2. Click __File__ --> __Import Appliance__ or double click the downloaded file __Univention-App-owncloud-ESX__ and click __Import__.

![Appliance](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C4-2%20Import%20Visual%20Appliance%2008.png)

3. Click __Agree__.

![Agree](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C4-3.png)
Now import starts.

## CHAPTER 5. CONFIGURING OWNCLOUD SERVER

1. Click __Start__. Wait 5 seconds to boot the server.

![Boot](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C5-1%20VM%20Start%2010.png)

2. In __ownCloud Appliance__ --> choose language and city details.

![Personal Details](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C5-2%20Settings%2011.png)

3. Type 192.168.178.1 in __Preferred DNS Server__ field and click __Next__.

![DNS](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C5-3%20Settings%2012.png)

4. In __Localization settings__ select your details.

![Personal Details](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C5-4Settings%2013.png)

5. In __Domain setup__ select __Manage users and permissions directly
on this system__ and click __Next__.

![Manage Users](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C5-5Settings%2015.png)

6. In __Account information__ type you organisation name and email id. Type password, only ASCII character passwords are allowed. Click __Next__ .

![Personal Details](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C5-6Settings%2016.png)

7. Type __Fully qualified domain name*__ and __LDAP base*__.

![LDAP](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/C5-7%20-%2017.png)

8. Click __CONFIGURE SYSTEM__.

![Configure System](https://github.com/rohit-kanwar/ownCloud-RH/blob/master/c5-8%20Settings%2018.png)
