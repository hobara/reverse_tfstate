# reverse_tfstate
Experimental repo to reverse the tfstate to the tf file, so that we don't have to manually create the tf file to from the scratch. Import the existing configuration as the current state and reverse it to the tf file. 

Phase 1
Write a simple ruby script that converts the tfstate file (input) to the tf file (output) in the terminal.

Phase 2
Create a JS file using JQuery that takes the input (JSON from the tfstate file) and converts it to the output (JSON for the tf file) in the browser.

Phase 3
Automate the creation of the tf file from the tfstate file through the tf module.
