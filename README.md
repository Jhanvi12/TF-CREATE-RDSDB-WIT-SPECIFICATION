# TF-CREATE-RDSDB-WIT-SPECIFICATION

**This is a terraform code to provision RDS Instance in AWS.**
```
1.**output-file.PNG** is the output image of AWS Console after we implemented the code and provisioned RDS.
2.**main.tf** has all terraform code which is required to provision RDS Instance in AWS with all its specifications .
3.**Provider.tf** has cloud provider information i.e AWS in our case . We can provision multi cloud here in provider . 
```
**Steps to run in your local machine assuming your TF and AWS Account is set** 
```
1.terraform init - By running the terraform init command , we can download the provider AWS Api , which will help to connect to remote backend
2.terraform validate - This command will tell you that your tf file is syntax wise correct or not.
3.terraform plan - This will check the complete resource and calculate the delta with previous changes.
4.terraform apply- This will actually create and provision resources in AWS Account .
5.Go to your AWS Account by console to check the resource creation.
```
