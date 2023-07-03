# Jupyter setup
* Provision the ec2 instance using tf and install juypter based AMI where the packages are installed.
* Using userdata start the juypter process
* Jenkins has two parameters such as autoapprove which is true and destroy which is false.
* Jenkins is getting trigerred using the webhook when pushes are happened to this repo,then terraform plan and apply will gets executed.
* To destroy the ec2 infra,someone has to check the destroy to true and run the pipeline manually from the console.
