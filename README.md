sa-hashicorp-vault
==================

[![Build Status](https://travis-ci.org/softasap/sa-hashicorp-terraform.svg?branch=master)](https://travis-ci.org/softasap/sa-hashicorp-terraform)


Example of usage (all parameters are optional)

Simple

  roles:
    - {
        role: "sa-hashicorp-terraform"
      }


Advanced:


  roles:
    - {
        role: "sa-hashicorp-terraform",
        apps_dir: /opt,
        terraform_version: 0.6.15,
        terraform_platform: linuc
      }



