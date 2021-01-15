# docker-boinc-client

[![](https://img.shields.io/docker/pulls/hdavid0510/boinc-client?style=flat-square)](https://hub.docker.com/r/hdavid0510/boinc-client) [![](https://img.shields.io/docker/cloud/build/hdavid0510/boinc-client?style=flat-square)]() [![](https://img.shields.io/github/issues/hdavid0510/docker-boinc-client?style=flat-square)](https://github.com/hdavid0510/docker-boinc-client/issues)  
Customized BOINC docker client on top of [official BOINC image](https://github.com/BOINC/boinc-client-docker).


---
## Tags

### latest
[![](https://img.shields.io/docker/v/hdavid0510/boinc-client/latest?style=flat-square)]() [![](https://img.shields.io/docker/image-size/hdavid0510/boinc-client/latest?style=flat-square)]()  
Build from `master` branch.

### dev
[![](https://img.shields.io/docker/v/hdavid0510/boinc-client/dev?style=flat-square)]() [![](https://img.shields.io/docker/image-size/hdavid0510/boinc-client/dev?style=flat-square)]()  
Build from `develop` branch.


---
## Environment Variables

### `BOINC_OPTION`
* Parameters that will be passed to the boinc client on init.
* **DEFAULT** _Blank; Use settings from configuration files from BOINC data directory._