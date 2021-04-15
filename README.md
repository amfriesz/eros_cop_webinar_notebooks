# EROS CoP Webinar Notebooks

## Before you start

Ensure you have a properly configured .netrc file with Earthdata login credentials. Earthdata login credentials are required when accessing NASA Earthdata cloud assets. These notebooks leverages a .netrc file to pass those credentials when making calls for data. The following python script can be use to create a .netrc file in the user profile/home directory: <https://git.earthdata.nasa.gov/projects/LPDUR/repos/daac_data_download_python/browse/EarthdataLoginSetup.py>.  

Additionally, a .netrc file can be created manually in the user profile/home directory with the following information:

```text
machine urs.earthdata.nasa.gov
login <USERNAME>
password <PASSWORD>
```
