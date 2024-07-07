##  Responsive  bootstrap Landing page website 

<--to run the project-->
The error message "This command is not available when running the Angular CLI outside a workspace" indicates that you're trying to use an Angular CLI command in a directory that is not an Angular project. The Angular CLI relies on specific files and configurations within the project workspace to function properly.

Here are ways to solve this error:

1. Navigate to the Angular project root directory:

Make sure you are in the directory that contains the angular.json file. This file is the main configuration for your Angular project.
Use the cd command in your terminal to navigate to the correct directory.
2. Check for missing or corrupted angular.json file:

The angular.json file is crucial for the Angular CLI to recognize the project. Ensure it exists in the root directory of your project.
If the file is missing, consider recreating the project using the Angular CLI commands: ng new <project-name>.
If the file is corrupted, try deleting it and running ng init in the project directory to regenerate it.
3. Verify global Angular CLI installation:

If you're using the ng command globally, ensure the Angular CLI is installed globally using npm install -g @angular/cli.
4. Check for typos:

Double-check that you are spelling the command correctly. Typos can lead to similar error messages. 


# Or Run it using Live server using Installed in you virtual studio
