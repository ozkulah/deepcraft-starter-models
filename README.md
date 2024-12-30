# DEEPCRAFT™ Starter Models
The repository contains all the DEEPCRAFT™ Starter Models. The Starter Models are various deep learning based projects for various use-cases and are designed to be projects that users can utilise as a starting point for building their custom applications. These projects have data and a project file that is ready to be used with DEEPCRAFT™ Studio. 

This repository is automatically pulled and content is automatically generated in DEEPCRAFT™ Studio, so to access the full content, it is recommended to access it through there.

## Usage
These projects are designed to be used through DEEPCRAFT™ Studio (https://www.imagimob.com/studio), and in general all users should access it that way.

## Contribution
All users are welcome to submit new models/projects, but they are subject to Infineon DEEPCRAFT™ Starter Model review process.

## Submission Process
To submit a project, you will need to create a pull-request with your data and DEEPCRAFT™ Studio project file (.improj). On top of that, we require that all project submissions have a readme file with the following information:
* Use-case
* Sensor settings
* How to collect more data and expand on it
* Potential next steps for users to have a path to investigate how to make this model production ready.

Once the project is ready, you can download and unpack the [Creat PR tool](https://api.imagimob.com/v1/Data/Object/create_pr.zip), and from there run

`python .\create_pr.py --path <project-path>`

where `<project-path>` is the root path of the starter model project. For more information review the tools' `README.md` file.

***NOTE:*** The pipline will automatically generate the pre-processing, model predictions and train some models based on the default best model selection from DEEPCRAFT™ Studio. If you would not like to have this, then please specify in the pull request if that should not be what should be published.