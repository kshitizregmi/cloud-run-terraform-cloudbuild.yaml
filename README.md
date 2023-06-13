# Clone these files on Google Console(GCP)



# Deploy using Terraform on Google Console
Initialize Terraform:

```bash
terraform init
```

Validate the Terraform configuration files:

```bash
terraform validate
```

Create and save the Terraform plan to a file:

```bash
terraform plan -out=tfplan
```

The -out=tfplan option saves the plan to a file named tfplan. You can choose a different filename if desired.

Review the planned changes:

```bash
terraform show tfplan
```

This step is optional but allows you to inspect the saved plan before applying it.

Apply the Terraform changes and deploy the infrastructure:

```bash
terraform apply tfplan
```
The tfplan argument specifies the plan file to apply. Terraform will prompt you to confirm the deployment. Enter yes to proceed.

Using the -out option and providing the plan file name ensures that you have a saved plan that can be used for later reference or to apply the changes without re-planning.

Again, make sure to adjust the commands according to your specific Terraform configuration and requirements.
