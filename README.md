ckanext-castate_od_schema
===========

Requirements
------------
Requires [ckanext-scheming](https://github.com/ckan/ckanext-scheming)


Installation
------------
To install ckanext-castate_od_schema for development, activate your CKAN virtualenv and do::

    git clone https://github.com/OpenGov-OpenData/ckanext-castate_od_schema.git
    cd ckanext-castate_od_schema
    python setup.py develop
    pip install -r requirements.txt


Config settings
---------------
```ini

ckan.plugins = ... custom_schema scheming_datasets
```