# Infrastructure folder

This folder contains the declarations and configurations of each control plane in its respective group. Argo CD is configured in the [bootstrap](../bootstrap/) folder to sync resources from this folder. The contents of this folder are grouped according to each business unit:

- Consumer services
- Manufacturing services
- Marketing services
- Playground

This allows you customize the number of control planes and their configurations according to the needs of each business unit.
