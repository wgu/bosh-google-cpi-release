# BOSH Google CPI release

This is a [BOSH](http://bosh.io/) release for the BOSH Google CPI.

## Releases
Please see [CHANGELOG.md] for details of each release.
<!--The Releases section is automatically generated. Do not edit-->
### CPI

|Version|SHA1|Date|
|---|---|---|
|[24.0.0](https://storage.googleapis.com/bosh-cpi-artifacts/bosh-google-cpi-24.tgz)|e2f77a0a8696b29fdb676cf447cfd9bc6841b648|2016-07-22|
|[24.1.0](https://storage.googleapis.com/bosh-cpi-artifacts/bosh-google-cpi-24.1.0.tgz)|dda781faa6673430ce77d708ac1c4be3cb763886|2016-07-25|
[//]: # (new-cpi)

### Stemcell

|Version|SHA1|Date|
|---|---|---|
|[3262.2 (Light)](https://storage.googleapis.com/bosh-cpi-artifacts/light-bosh-stemcell-3262.2-google-kvm-ubuntu-trusty-go_agent.tgz)|f46d82a6ae6e89a5635cb3122389f0c8459a82e0|2016-07-22|
|[3262.2 (Heavy)](https://storage.googleapis.com/bosh-cpi-artifacts/bosh-stemcell-3262.2-google-kvm-ubuntu-trusty-go_agent.tgz)|f294226d3ade9e27b67e4ef82b8cd5d3b4e23af7|2016-07-25|
[//]: # (new-stemcell)

## Usage
If you are not familiar with [BOSH](http://bosh.io/) and its terminology please take a look at the [BOSH documentation](http://bosh.io/docs).

## Deploy a BOSH Director on Google Cloud Platform
Complete instructions for deploying a BOSH Director are available in the [docs/bosh/README.md](docs/bosh/README.md) file.


## Deploy other software
After you have followed the instructions for deploying a BOSH director in [docs/bosh/README.md](docs/bosh/README.md), you may deploy releases like CloudFoundry by following the links below:

* [Deploying Cloud Foundry on Google Compute Engine](https://github.com/cloudfoundry-incubator/bosh-google-cpi-release/blob/master/docs/cloudfoundry)

## Contributing
For detailes on how to contribute to this project - including filing bug reports and contributing code changes - pleasee see [CONTRIBUTING.md].

[CHANGELOG.md]: CHANGELOG.md
[CONTRIBUTING.md]: CONTRIBUTING.md
