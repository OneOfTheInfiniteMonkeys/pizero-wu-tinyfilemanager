# PiZero-WU Tiny File Manager


[![Live demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg?style=flat-square)](https://tinyfilemanager.github.io/demo/)
[![Live demo](https://img.shields.io/badge/Help-Docs-lightgrey.svg?style=flat-square)](https://github.com/OneOfTheInfiniteMonkeys/pizero-wu-tinyfilemanager/wiki)
[![GitHub Release](https://img.shields.io/github/release/qubyte/rubidium.svg?style=flat-square)](https://github.com/OneOfTheInfiniteMonkeys/pizero-wu-tinyfilemanager/releases)
 [![GitHub License](https://img.shields.io/github/license/OneOfTheInfiniteMonkeys/pizero-wu-tinyfilemanager.svg?style=flat-square)](https://github.com/OneOfTheInfiniteMonkeys/pizero-wu-tinyfilemanager/blob/master/LICENSE) 

> Based on TinyFileManager by prasathmani, PiZero-WU TinyFileManager is simple web based file manager that is a fast and small file manager with a single file, multi-language ready web application for storing, uploading, editing and managing files and folders online via web browser. The Application runs on PHP 5.5+, It allows the creation of multiple users and each user can have its own directory and a build-in support for managing text files with cloud9 IDE and it supports syntax highlighting for over 150+ languages and over 35+ themes.

The PiZero-WU fork includes specific extensions to permit viewing of special file types rendered by a fork of pyembrodery.

## Demo
[Demo](https://pizero-wu-tinyfilemanager.github.io/demo/)

 Login Details : admin/admin@123 | user/12345


## Documentation
Tinyfilemanager is highly documented on the [wiki pages](https://github.com/oneoftheinfinitemonkeys/pizero-wu-tinyfilemanager/wiki).


[![Tiny File Manager](screenshot.gif)](screenshot.gif)

## Requirements

- PHP 5.5.0 or higher.
- Fileinfo, iconv, zip, tar and mbstring extensions are strongly recommended.
- pyemroidery fork

## How to use

Download ZIP with latest version from master branch.

Just copy the tinyfilemanager.php to your webspace - thats all :)
You can also change the file name from "tinyfilemanager.php" to something else, you know what i meant for.

Default username/password: **admin/admin@123** and **user/12345**.

:warning: Warning: Please set your own username and password in `$auth_users` before use. password is encrypted with <code>password_hash()</code>. to generate new password hash [here](https://tinyfilemanager.github.io/docs/pwd.html)

To enable/disable authentication set `$use_auth` to true or false.


### :loudspeaker: Features 

- :cd: Open Source, light and extremely simple
- :iphone: Mobile friendly view for touch devices
- :information_source: Basic features likes Create, Delete, Modify, View, Quick Preview, Download, Copy and Move files 
- :arrow_double_up: Ajax Upload, Ability to drag & drop, upload from URL, multiple files upload with file extensions filter 
- :file_folder: Ability to create folders and files
- :gift: Ability to compress, extract files (`zip`, `tar`)
- :sunglasses: Support user permissions - based on session and each user root folder mapping
- :floppy_disk: Copy direct file URL
- :pencil2: Cloud9 IDE - Syntax highlighting for over `150+` languages, Over `35+` themes with your favorite programming style
- :page_facing_up: Google/Microsoft doc viewer helps you preview `PDF/DOC/XLS/PPT/etc`. 25 MB can be previewed with the Google Drive viewer
- :zap: Backup files and IP blacklist and whitelist
- :mag_right: Search -  Search and filter files using `datatable js`
- :file_folder: Exclude folders and files from listing
- :globe_with_meridians: Multi-language(20+) support and for translations `translation.json` is file required
- :bangbang: lots more...


### <a name=license></a>License, Credit  

- Available under the [GNU license](https://github.com/oneoftheinfinitemonkeys/pizero-wu-tinyfilemanager/blob/master/LICENSE)
- Original concept and development by github.com/alexantr/filemanager
- CDN Used - _jQuery, Bootstrap, Font Awesome, Highlight js, ace js, DropZone js, ekko-lightbox js, and DataTable js_
- To report a bug, please file an [issue](https://github.com/oneoftheinfinitemonkeys/pizero-wu-tinyfilemanager/issues)
- [Contributors](https://github.com/prasathmani/tinyfilemanager/wiki/Authors-and-Contributors)

### Attribution
[![Paypal](https://img.shields.io/badge/Donate-Paypal-lightgrey.svg?style=flat-square)](https://www.paypal.me/prasathmani) - Donations to the author of the master branch author

Donations to the fork author - None
