# MeshCentral Material UI:
Custom UI for MeshCentral based on Material UI

![image](https://github.com/DaanSelen/meshcentral-material/assets/80752476/ca53d034-fd28-4d69-ba75-e68692112632)

# Installation guide (of this version):

Clone this repository (if you have git installed, if not: download it here: [Git Download](https://git-scm.com/downloads))<br>

```git clone https://github.com/DaanSelen/meshcentral-material```<br>

after that move or copy the folder src/meshcentral-web (or parts of it IF YOU KNOW WHAT YOU ARE DOING) into your installed MeshCentral root folder, where meshcentral-files and meshcentral-data is located.
Once that's done, restart the MeshCentral server using the guide instructed service file. Using Systemd this is done like this:<br>

```sudo systemctl restart meshcentral.service```<br>

After that browse to your MeshCentral server IP or domain.

The meshcentral-web folder, along with its custom files, must be placed in the root folder of your MeshCentral instance (where meshcentral-data and meshcentral-files).

#End of Official repository Readme.

Notes (unclear instruction from main branch, will be looked into)

Requires MeshCentral to be configured with the following options: (maybe not nightMode, but it was designed with that configured)

```
"domains": {
  "": {
    "hide": 5,
    "nightMode": 1,
    "minify": false
  }
},
```
