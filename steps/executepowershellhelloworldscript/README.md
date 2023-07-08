# Step 1
Create a new `Blueprint` and include a description.

* Create an `Execute Windows Script` Step in the Blueprint.
* Create Parameters:
    * `Windows Node`
    * `Windows Credentials`
* Populate the newly created parameters into the Step.
* Populate the Script: `Write-Host "Hello, World!"`.
* Write a comment for the Step.

# Step 2
After you've completed creating the Blueprint, navigate to Plan. 
Create a `Plan Tree`.
* Create a Plan
* Create Values for your Parameters:
    * `Windows Node`
    * `Windows Credentials`
* Populate the Values into the Plan

# Step 3
Once the Plan is populated, navigate to Run. `Run` the Job.