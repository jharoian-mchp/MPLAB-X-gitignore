# MPLAB® X .gitignore

MPLAB X uses a project folder format that needs certain files and folders excluded for moving it between different computers and operating systems.

Specifically, any file that contains an absolute path or other machine/OS specific settings should not be committed to a git repository.

## Use

Copy the .gitignore file from this repo into the root directory of your git repository.  This is typically the directory one level above the "project_name.X" folder as the project folder name with the .X suffix is required for MPLAB X to recognize the folder as a project.

A second .gitignore file called X.gitignore has been added to the repository.  This file can be used at the project.X/.gitignore folder level and needs to be renamed .gitignore to be used.  It was developed as the template for MPLAB X's .gitignore "new file" template.

## Additional Information

The Microchip Developer Help wiki contains more detailed information on the specific files and folders not recommend for inclusion:
[Working with Version Control Systems - Developer Help (microchipdeveloper.com)](https://microchipdeveloper.com/mplabx:version-control-working-with)

