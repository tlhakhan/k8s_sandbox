# README
This repository holds scripts to help with Kubernetes deployment and testing in my homelab.

| playbooks | description
 --- | ---
`reset.yml` | Revert the VMs to the snapshot Id of 1.
`create_snap.yml` | Removes all VM snapshot and creates one to use as the latest point to revert.
