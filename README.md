# 4640-w10-lab-start-w25

## Getting Started

### Add public key to AWS
1. Navigate to the `scripts` folder of the project directory (ex: `<insert_some_path_here>/acit-4640-lab_wk11/scripts`)
2. Run the following command to execute the import key script
```
./import_lab_key ~/.ssh/aws.pub
```
We are passing in the `aws.pub` public key we made earlier as an argument into the script `import_lab_key` for it to add the key to our AWS account.

### Creating Infrastructure using Terraform
1. Navigate to the `terraform` folder of the project directory (ex: `<insert_some_path_here>/acit-4640-lab_wk11/terraform`)
2. Run the following command to initialize the directory:
```
terraform init
```
3. See what kinds of steps terraform would make to create the infrastructure described in the terraform file using the following command:
```
terraform plan
```
4. Create the infrastructure as described by the output of the `terraform plan` command using the following command:
```
terraform apply
```
