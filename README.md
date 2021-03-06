# SFDX Simple App

> **Important:** Salesforce DX is available as a Beta. Salesforce DX isn’t generally available unless or until Salesforce announces its general availability in documentation or in press releases or public statements. All commands, parameters, and other features are subject to change or deprecation at any time, with or without notice. Don't implement functionality developed with these commands or tools.

The Salesforce Developer Experience (SFDX) starts with source code living in your version control system.

## Set Up the Salesforce DX Project

Our first goal is to set up a developer project which we'll use to modify our application. It starts by cloning the repository. Use the command ...

    git clone https://github.com/forcedotcom/sfdx-simple-beta.git

… or ...

    git clone git@github.com:forcedotcom/sfdx-simple-beta.git

… to clone the repository. Then, open the directory.

    cd sfdx-simple-beta
    
## Steps

Follow Instructions in this Quip Doc - https://salesforce.quip.com/aodpARLkqmAf

## Resources

For details on using sfdx-simple-beta, please review the [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev).

## Description of Files and Directories  

* **sfdx-project.json**: Required by Salesforce DX. Configures your project.  Use this file to specify the parameters that affect your Salesforce development project.
* **config/project-scratch-def.json**: Sample file that shows how to define the shape of a scratch org.  You reference this file when you create your scratch org with the force:org:create command.   
* **force-app**: Directory that contains the source for the sample Force.com app and tests.   
* **.project**:  Required by the Eclipse IDE.  Describes the Eclipse project. 
* **.gitignore**:  Optional Git file. Specifies intentionally untracked files that you want Git (or in this case GitHub) to ignore.

## Issues

Please log issues related to this repository [here](https://github.com/forcedotcom/sfdx-simple/issues).
