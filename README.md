# webflow-to-django
A script to convert exported webflow assets to neat django templates.

Import Webflow files into Django project.

Example usage:
```bash
python scripts/import_webflow.py web export.webflow.zip
```

```bash
python import_webflow.py <django_app_name> <export_zipfile_name>
```

Note: you must be root of the project to run this script.


Video showing how to use the basic form of the script is here:
https://www.youtube.com/watch?v=ohJzBkgSIMQ


## Prerequisites
```Python 3.7+```
```pip install bs4 send2trash```
