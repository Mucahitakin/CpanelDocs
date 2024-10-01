# Almalinux and Cpanel Install Documentation


### How to install almalinux 


First of all, the operating system of your machine is very important. If you are going to use `php 7.4 php 7.3`, I recommend you to install the Almalinux 8 operating system on your machine. If your hosting provider does not support this file, you will need to find the iso file, I am leaving the iso file I found by natro, which is currently up to date, as a link below.

`https://mirror.natro.com/almalinux/8.10/isos/x86_64/`

After uploading the downloaded iso file we proceed with the installation.

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel1-dQJtkM1YQd.png" height='400' width='400'>

- We start the installation by saying Install


<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel2-7VpDK7DwGp.png" height='400' width='400'>

- Start install

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel3-759ndntaFy.png" height='400' width='400'>

- We continue our installation phase by choosing our language.

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel4-gUN1ICm1wt.png" height='400' width='400'>

- We define our disk for installation.

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel7-FkG1d44KGf.png" height='400' width='400'>

- Now it's time to set the internet settings, we immediately turn it to “on” and it automatically receives the ip address via DHCP. 

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel8-ZmFKDTcIKX.png" height='400' width='400'>

- Select the language of our keyboard.

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel10-D2K2ks1KCc.png" height='400' width='400'>

- Immediately afterwards we create our password for root, please avoid known passwords and short passwords for your security.

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel11-JswpOC1Cmi.png" height='400' width='400'>

- If you have successfully completed all operations, the main screen should look like this.

<img src="http://mucahitakin.com/blog/akinimg/almalinux-nasil-kurulur-gorsel12-2fc0xCL3Jg.png" height='400' width='400'>

- We say `Begin Installation` and the installation starts. Although the installation time varies according to your system specifications, it usually takes between 8-10 minutes.

I am a backend php developer, so mysql and php related versions are of great interest to me.


You can use any of these isos you need.

### Installation Guide - Installation

To install cPanel & WHM on your server, run the following command:

`cd /home && curl -o latest -L https://securedownloads.cpanel.net/latest && sh latest`

This command changes your session to the home directory, downloads the latest version of cPanel & WHM, and runs the installation script.

All you have to do is run the code above and after about 15 minutes or 20 minutes your process will be completed.

And when the process is finished, it will give an output as succesfull. When it gives this output 

Your ip address: You can access the whm panel from port `185.126..:2087`.

your username is usually set as default  `root` 

Your password is the password with which you connect to the terminal. 

You have successfully completed the Cpanel installation. After that you can set the php versions you will use.

You can access this field by typing EasyApache4 in the search field of WHM.

Then you say Customize in the Currently Installed Packages section.

Then, after selecting the php version and php extension sections, we say review.

We make the necessary installations by clicking the Provision button. 

 
