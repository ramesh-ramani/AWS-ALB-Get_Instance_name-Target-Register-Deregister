This script will take the Names of the Instances (That you need to perform maintenace on) as input, it will then go and find the ALB and Corresponding Target Groups that it's a part of and De-Register the instances from the Target Group. It will then ask you if you want to re-add the Instances back to the Target Groups. If yes, it will add all of them back to where they were. 

This script will be useful when you want to take Load balancers out of the respective targets to perform maintenace on them. 
