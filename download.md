---
layout: page
title: Manjaro Installation Media
permalink: /download/
---


Manjaro's official Download page has moved to our new site.
Please visit [**manjaro.org**](https://manjaro.org/community-editions/).


 ![XFCE]({{ site.baseurl }}/images/desktop-environment-xfce.png "XFCE edition")
 ![KDE]({{ site.baseurl }}/images/desktop-environment-kde.png "KDE edition")
 ![NET]({{ site.baseurl }}/images/net-edition.png "Net edition")
 ![GNOME]({{ site.baseurl }}/images/desktop-environment-gnome.png "GNOME edition")
 ![LXDE]({{ site.baseurl }}/images/desktop-environment-lxde.png "LXDE edition")
 ![MATE]({{ site.baseurl }}/images/desktop-environment-mate.png "MATE edition")
and more...

<iframe width="640" height="360" src="https://www.youtube.com/embed/H4DKR5TeorQ" frameborder="0" allowfullscreen></iframe>

Both 32 and 64 bit versions of Manjaro are available in the following flavours (i.e. with the following desktop environments pre-installed):


## XFCE

  - [**get Manjaro**](https://manjaro.org/get-manjaro/)

## KDE

  - [**get Manjaro**](https://manjaro.org/get-manjaro/)

## Net-Edition

The NET edition of Manjaro provides a base installation without a pre-installed display manager, desktop environment, or any desktop software applications. It allows you to build your own version of Manjaro from the ground up.

  - [**get Manjaro**](https://manjaro.org/get-manjaro/)

### Other flavours

Some additional Desktop Environment and preconfigured Window Managers are available with our [**Community Editions**](https://manjaro.org/community-editions/).

## How to verify our install medias

Please read the according chapter (from page 19 onwards) in our [Manjaro Beginners Guide](https://sourceforge.net/projects/manjarolinux/files/release/16.06.1/manjaro-16.06.1-documentation.pdf) on how to verify your downloaded install media. Beginning with our 16.06.1 release, we also provide gpg verifcation. Therefore you need to get the [developer signatures](https://github.com/manjaro/packages-core/raw/master/manjaro-keyring/manjaro.gpg) from Manjaro.

**Example:**

```
wget https://github.com/manjaro/packages-core/raw/master/manjaro-keyring/manjaro.gpg
gpg --import manjaro.gpg
gpg --verify manjaro-xfce-16.06.1-x86_64.iso.sig
```
