# Building and Applying vSmart Device Templates
This directory contains the files needed to create a new vSmart device
template and apply it to all vSmarts. This is a required step before
application routing policies can be applied to the fabric.

Relevant files:
  * `build_vsmart_template.py`: Creates a new vSmart device template using the
    factory default vSmart feature templates, then applies it to all vSmarts.

**Note:** Check the `data_ref/` directory for example JSON responses from all
API calls.
