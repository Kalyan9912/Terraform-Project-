terraform is a one of the used infrastructure as a code tool.it helps to automate and  create the infrastructure by writing terraform script 
it has multiple file to create infrastructure with file extension of .tf  like provider.tf, variable.tf,outputs.tf,terraform.tfvars,main.tf             
1. provider.tf has a content like which type of provider we are using like aws,google cloud,ibm cloud,oracle cloud etc.. in this we need mention provider ,region and access secret key if we want.
2.variabl.tf has a content like when we are going create infrastructure we will hard code some values  but by mentioning the variables we can manage variable values what ever we want.                 
3 terraform.tfvars file has a content of values that we want to pass in place of variables,here in this we need to mention values for the variables.        
4 outputs.tf file has a content to print the output to display some results like ip, instances id etv.. by printing the value of infrastructure we understand that infrastructure output so that we dont need to go and opej to see values of that service instead of that we can print directly when we create infrastructure                             
5 main.tf file has a content related to main things which we are going to create in a cloud .it is the main file to create infrastructure .                   
otherthan this we have multiple files to create infrastructure that will create automatically to store infrastructure info.
