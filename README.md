# PisaSales ECS

## Branches

- `main`:
  - contains the base for PisaSales running on ECS
  - contains the statements to create a base image (AMI) for the latest published version (including patches) of PisaSales, Tomcat, WebClient and MobileClient 
- `customer`:
  - inherits from `main`
  - adjustments to configuration takes place in Parameter Store of AWS Account for `customer`
  - additionally needed Jars will be added to this branch

