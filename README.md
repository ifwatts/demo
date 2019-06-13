# Think 2019 Demo Repo
Storing some templates and services for IBM Cloud Automation Manager demonstrations

To use Lamp Stack Deployment.json 
## Steps
1. import the google cloud template from this repo at https://github.com/ifwatts/demo/tree/master/Google/terraform/hcl/lamp into your CAM instance.
2. import the service definition (choose the branch that matches your CAM release) from this repo at https://github.com/ifwatts/demo/blob/master/Lamp%20Stack%20Deployment.json
3. Edit the Service
  * click on each template in the service and set the cloud connection to a valid entry for this environment
  * click on the parameters tab and edit the "cam_ip" variable to have the cam instances ip or hostname along with the port.  eg: 10.10.10.10:300000  This is used to make a URI that is sent in email apon completion of the service to the user.
