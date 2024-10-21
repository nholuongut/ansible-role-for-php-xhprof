# Ansible Role: PHP-XHProf

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Installs PHP [XHProf](http://php.net/manual/en/book.xhprof.php) on Linux servers.

> **Note**: The XHProf extension has been on life support since Facebook abandoned active development around 2015.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    workspace: /root

Where XHProf setup files will be downloaded and built.

    xhprof_version: "2.1.2"

The version of XHProf to download.

    xhprof_download_url: https://github.com/longxinH/xhprof/archive/v{{ xhprof_version }}.zip
    xhprof_download_folder_name: xhprof-{{ xhprof_version }}

The URL from which XHProf will be downloaded.

    xhprof_output_dir: /tmp

Directory where XHProf runs are stored.

    php_xhprof_lib_dir: /usr/share/php/xhprof_lib

Directory where the XHProf PHP library is stored.

    php_xhprof_html_dir: /usr/share/php/xhprof_html

Directory where the XHProf UI is stored.

## Dependencies

  - nholuong.php

## Example Playbook

    - hosts: webservers
      roles:
        - nholuong.php-xhprof

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟