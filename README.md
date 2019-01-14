# Terraform vSphere Module

For Virtual Machine Provisioning with (Linux).

1. Set the vSphere Environment Variables:

export VSPHERE_USER="<Username>@vsphere.local"
export VSPHERE_PASSWORD="<Password>"
export VSPHERE_SERVER="<IP Address>"
export VSPHERE_ALLOW_UNVERIFIED_SSL=true

2. Run terraform init

3. Run terraform plan

4. Run terraform apply

## Deploys (Single/Multiple) Virtual Machines to your vSphere environment

This Terraform Demo deploys single or multiple virtual machines of type (Linux) with following features:

* Ability to deploy Multiple instances.
* Ability to set IP and Gateway configuration for the VM.
* Ability to choose vSphere resource pool or fall back to Cluster/ESXi root resource pool.
* Ability to deploy Windows images to WorkGroup or Domain.

> Note: For module to work it needs number of required variables corresponding to an existing resources in vSphere. Please refer to variable section for the list of required variables.

## Usage

Following example contains the bare minimum options to be configured for VM deployment.

```

## Authors

Edited by Arslan Saeed

## License

[MIT](LICENSE)