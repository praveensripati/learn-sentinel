# learn-sentinel

High level sequence of steps
https://www.hashicorp.com/resources/writing-and-testing-sentinel-policies-for-terraform

1. Write a Terraform configuration that creates the resource your policy will restrict.

1. Create a Terraform workspace that uses your Terraform configuration.

1. Run a plan against your workspace using the remote backend.

1. Generate mocks against your plan in the Terraform UI.

1. Write a new Sentinel policy.

1. Test your Sentinel policy with the Sentinel Simulator

1. Revise your policy and test cases until they all pass.

1. Deploy your policy to an organization on a Terraform server.


## Documentation

1. Sentinel documentation
    - https://docs.hashicorp.com/sentinel
    - https://docs.hashicorp.com/sentinel/intro

## Sentinel policies

1. Writing and Testing Sentinel Policies for Terraform
    - https://www.hashicorp.com/resources/writing-and-testing-sentinel-policies-for-terraform

1. Sentinel Policies
    - https://github.com/hashicorp/terraform-sentinel-policies/tree/main

## Mocking

1. Mocking Terraform Sentinel Data
    - https://developer.hashicorp.com/terraform/cloud-docs/policy-enforcement/sentinel/mock

## Alternatives

1. Checkov
    - https://www.checkov.io/