# planning-center-live
This script makes it possible to find the next plan of a specific Planning Centre Online service type and to open this plan in full screen mode in the Firefox browser. The service type and the access data are defined in the script. 

Instructions
- Install Plain XUbuntu 22.04.4 LTS (Maybe other Distributions also Work - but not Tested)
- Install jq if it is not already installed:
  ```shell
  sudo apt-get install jq
  ```
- Save the shell script as get_next_plan.sh and make it executable:
  ```shell
  chmod +x get_next_plan.sh
  ```
- Customize the script by entering the desired service type and credentials.
- Generate the Credentials here: https://api.planningcenteronline.com/oauth/applications
- Run the script in a Terminal:
  ```shell
  ./get_next_plan.sh
  ```
  
The script will list all available service types, find the next plan for the specified service type, and open it in full-screen mode in the Firefox browser.
