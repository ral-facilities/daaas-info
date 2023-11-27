# daaas-info

[DAaaS Tech Updates](https://ral-facilities.github.io/daaas-info/index.html) github pages.

## Update the information

### Get the source

`git clone git@github.com:ral-facilities/daaas-info.git`

### Install Prerequisites

    cd daaas-info`  
    python3 -m venv env`    
    source env/bin/activate`    
    pip3 install -r requirements.txt`

### Update source files

Only update the RST files in the **source** folder.

Follow [RST file guidelines](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html)

### Make HTML files

    make html

This will generate html files in **docs** folder.

By default, the generated html files would be in **docs/html**. The Makefile script moves them to **docs** folder to accommodate the github page settings.

### Commit and push the code, then check the site

After code pushed, the site should be automatically updated. Check [github page settings](https://github.com/ral-facilities/daaas-info/settings/pages) if anything unexpected.

