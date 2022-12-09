# GCP EGRESS NAT INGRESS LB

This repository consists of Terraform templates to bring up a F5XC GCP sites with Ingress LB and Egress NAT GW and SMG.

## Usage

- Clone this repo with: `git clone --recurse-submodules https://github.com/cklewar/f5-xc-uc-gcp-smg-nat-lb`
- Enter repository directory with: `cd gcp egress nat ingress lb`
- Obtain F5XC API certificate file from Console and save it to `cert` directory
- Pick and choose from below examples and add mandatory input data and copy data into file `main.py.example`.
- Rename file __main.tf.example__ to __main.tf__ with: `rename main.py.example main.py`
- Initialize with: `terraform init`
- Apply with: `terraform apply -auto-approve` or destroy with: `terraform destroy -auto-approve`

## GCP Egress NAT Ingress LB module usage example

````hcl
````