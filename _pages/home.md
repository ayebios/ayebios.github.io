---
layout: single
permalink: /
hidden: true
title: AyeBIOS™ 
header:
  overlay_color: "#4d2e00"
  overlay_image: https://upload.wikimedia.org/wikipedia/commons/e/ed/Sega-Saturn-US-Motherboard-M1-03.jpg
  actions:
    - label: "<i class='fas fa-fw fa-handshake'></i> Join us"
      url: "/join-us/"
excerpt:
  <b>This is an AyeBIOS™ site<br>
  meant for academic purposes</b><br>
  <small>
  <a href="about/">More about AyeBIOS™  </a>
  </small>
feature_row:
  - image_path: /assets/images/image1.jpg
    alt: "Highlight1"
    title: "Simpler"
    excerpt: "With AyePages it is simpler to customise your GitHub Pages site as per your choice, just a fork would serve the purpose. <br><br><br>"
    url: "/Highlight2/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/image2.jpg
    alt: "Highlight2"
    title: "Faster"
    excerpt: " All you need to do is just take 2 minutes of your time and that all to fork. Ofcourse, a bit longer to learn, try out a free course [here](https://ayeai.xyz/site/courses/github-pages-site-in-2-minutes-with-ayepages/) <br><br><br>"
    url: "/Highlight3/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/image3.jpg
    alt: "Highlight3"
    title: "Flexible"
    excerpt: " AyePages is flexible and you can adpot it as per needes and choices. You may use it as blog, personal profile, information site and its your choice!<br><br><br>"
    url: "/Highlight2/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---

<iframe allowfullscreen="false" frameborder="0" mozallowfullscreen="false" src="https://docs.google.com/presentation/d/e/2PACX-1vT5K9ijpA0fuuS4OJTQMwoMaQrZm5dMCXisLRBgVzxQ7I5312_uHAqZvvJIA_5KRrG02t45MotrTj_a/embed?start=true&loop=true&delayms=300&rm=minimal" webkitallowfullscreen="false" width="100%" height="77"></iframe>

{% include feature_row %}

आईबायोस (AyeBIOS)
Localized open source BIOS (as per the license) derived from SeaBIOS
The localized source code has been created using Hindawi Programming System
To see, access or use the original sources from which these files have been derived the following, or equivalent may be used.

# This is only an example and may differ on different medium of distribution.
git clone https://github.com/ayebios/ayebios
cd ayebios
git checkout upstream
The localized versions are shared for academic purposes only
NOTICE
All copyrights and notices in the original source code are available under the "upstream" branch.

The Hindawi ported versions are binary deliverables delivered along with sources under the "upstream" branch. Under jurisdictions where the translator has copyright over original translation, the Hindawi ported version must include the additional copyright notices even if not explicitly mentioned in the original or derivative source code files.

Copyright (C) 2021 Abhishek Choudhary

The license terms for all derivatives shall be under AyeAI Singularity Public License latest version, unless impunged by any of the terms of the original license. These artifacts, text, source code or other deliverables are provided AS IS, with NO WARRANTY and NO LIABILITY. These artifacts, text or source code MUST NOT BE USED for any business critical or safety critical systems.

In case any of the terms of this license stands defective, it shall have no implication on the licensing terms and conditions of the original source code from which these have been derived.

AyeAI, AyeAM, Hindawi Programming System, AyeBIOS are trademarks or registered trademarks of Abhishek Choudhary. All other trademarks are acknowledged as belonging to their respective owners.

All disputes are subject to courts in Hyderabad, Telangana, India only.

/NOTICE
From the original README
Welcome to the AyeBIOS project! This project implements an X86 legacy bios that is built with standard GNU tools.

Please see build and developer information at:

http://ayebios.org/Developer_Documentation

For the impatient, AyeBIOS is built for QEMU and tested on QEMU with:

make qemu -bios out/bios.bin

AyeBIOS can be configured with kconfig. To change the default configuration one can run "make menuconfig" prior to running "make".

For other types of builds, and for more detailed developer documentation, please see the online documentation listed above.


