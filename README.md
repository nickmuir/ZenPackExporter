# ZenPackExporter
Script to export ZenPacks from Zenoss 4 via the command line.

Providing the script with a ZenPack name will create the objects.xml and the skins folder.  The script can also build the ZenPack egg and drop it in the requested folder.

```

usage: zenpackexport.py [-h] -z PACKNAME [-b] [-p EXPORTPATH]

Export Zenpacks from the cli

optional arguments:
  -h, --help            show this help message and exit
  -z PACKNAME, --zenpack PACKNAME         ZenPack name to export
  -b, --build                             Build and export an egg
  -p EXPORTPATH, --path EXPORTPATH        Path to export egg to

```

Most of the code copied from ZenPackManager.py of Zenoss 4.2.5 
