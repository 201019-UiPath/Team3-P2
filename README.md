# Team3-P2

## Project Description

Automation project for adding free games to a user's associated game account, and installing them to a specific machine after addition. Made with UiPath Studio 2019.10.5, by Jacob Jennings, Lindsey Weber, and Vincent Weis.

## Technologies Used

* UiPath Studio 2019.10.5
* UiPath Orchestrator
* UiPath Robot
* Outlook
* Excel

## Features

List of features ready and TODOs for future development
* Automation checks for launchers installed on user's computer
* Free games scraped from Steam and Epic websites
* Scraped games presented to user for adding to library and installation on user's computer
* Email provided to user at end of automation containing Excel files of games added and installed

## Getting Started
   
To Clone:
`git clone https://github.com/201019-UiPath/Team3-P2.git`

- Once cloned, in Game Getters main project, open up Data folder
- In Config.xlsx, in the Settings sheet, you will find the values for assets to create either in Orchestrator or set the values of these in the Config file
- You will need to set the value for EmailCredential to the email account where you would like the automation to send emails from
- EpicCredential and Steam_Credential values will also need to be set for the Steam and Epic accounts you wish to use during the automation

## Usage

> Once cloned and assets created in the Config.xlsx file or in Orchestrator, you can publish the automation to Orchestrator to run through UiPath Robot. To publish, click the Publish button in UiPath Studio, set the version number you wish to use, and click Publish. Once published, assign the automation to a robot to be run!

## Contributors

> Jacob Jennings (jjennings510)
> Vincent Weis (vrobweis)
> Lindsey Weber (lw3b3r)

## License

This project uses the following license: [MIT License](https://github.com/201019-UiPath/WeberLindsey-Project1/blob/main/LICENSE).
