# Troubleshooting

## Sign up related issues

### Email rejected during sign-up

* Change email address. Best is to use their school domain XX@smu.edu.sg 

### Free Credits

* Put a valid credit card to unlock USD$200 cloud credits on IBM Cloud.  

## Common issues

## Error 404, pages not loading, uploading of assets taking a lot of time or other Web related errors

* Ensure WiFi or 4G signal is strong
 
* Use Firefox browser or other browser
 
* Clear cache, log out and log back into IBM Cloud

## IBM Cloud services not linking up

* Provision services in the same region. There are some CDN routing issues sometimes. 
(e.g. iCOS in Dallas, Watson Machine Learning also should be Dallas). If still error, try to spin up services in US, its the most reliable. 

## Code not working or churning ERROR message 

* Check for the latest version of tools - IBM CLI, Cacli, Python etc

## Problem deploying Node-RED

* Reduce memory allocation to 128 or 192 MB 

## Issues with cloud.annotations.ai

* Ensure Watson Machine Learning (WML) instance is in Dallas or London