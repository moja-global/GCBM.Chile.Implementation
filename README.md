# Implementation of the Generic Carbon Budget Model (GCBM) in Chile
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

## About

This repo contains the implementation of the GCBM with the data on Chilean forest REDD+ activities, based on the offitial GCBM distribution (using the Standalone implementation), it includes data injection codes made by Chile in order to modify the default parameters of the model, reflecting the assumptions that Chile makes for REDD+ accounting purposes. This products consists in a proof of concept and a work of progress, that uses the Los Rios Region, in southern Chile, as pilot area.

The parameters were set to reflect the assumptions taken by Chile in the elaboration of its Forest Reference Emissions Level / Forest Reference Level, [FREL/FRL](https://redd.unfccc.int/files/chile_mod_sub_final_01032017_english.pdf), submitted in August 31th, 2016.

The methods and results of this work were compiled into the [technical document](https://moja.global/wp-content/uploads/2020/04/Chile_GCBM_Pilot_Technical_Document.pdf) "Modelling forest carbon dynamics for REDD+ using the Generic Carbon Budget Model (GCBM)", were more details can be found.

The preprocessing steps conducted to transform the offitial Chilean data into the GCBM format can be found in [this repo](https://github.com/moja-global/GCBM.Chile.Data_Preprocessing)

**Disclaimer**: The results derived from the use of this algorithms do not necessarily reflect the positions of the Government of Chile for REDD+ accounting or any other purpose.

## Environment

This repo was tested using Python 2.7 on a Windows 10 OS (64 bit), the version of the GCBM build is: 2019-10-22, SHA-1: 1f3f57fc1800ee1abd58906a13671599e7ac8de4


## Instructions

1. Go to releases and download the Standalone executable
3. follow the install steps described in documentation/GCBM_Installation_Guide_2019_03_04.docx
3. Open the run_all.bat with a text editor and modify the path of the python installation to match your own 
4. Run the entire model using the run_all.bat file or step by step by using the .bat files starting with a number (01, 02, 03, 04, 05)

*There is a chance that the sqlalchemy library causes an error during install ("No matching distribution found for sqlalchemy"), you can solve it by openning a command prompt in C:/Python27/Scripts (replace C:/Python27 for your corresponding Python 2.7 installation if necessary) and type __pip install sqlalchemy__ , the you can follow with the described installing steps


## How to Get Involved?  

moja global welcomes a wide range of contributions as explained in [Contributing document](https://github.com/moja-global/About-moja-global/blob/master/CONTRIBUTING.md) and in the [About moja-global Wiki](https://github.com/moja-global/.github/wiki).  

  
## FAQ and Other Questions  

* You can find FAQs on the [Wiki](https://github.com/moja.global/.github/wiki).  
* If you have a question about the code, submit [user feedback](https://github.com/moja-global/About-moja-global/blob/master/Contributing/How-to-Provide-User-Feedback.md) in the relevant repository  
* If you have a general question about a project or repository or moja global, [join moja global](https://github.com/moja-global/About-moja-global/blob/master/Contributing/How-to-Join-moja-global.md) and 
    * [submit a discussion](https://help.github.com/en/articles/about-team-discussions) to the project, repository or moja global [team](https://github.com/orgs/moja-global/teams)
    * [submit a message](https://get.slack.help/hc/en-us/categories/200111606#send-messages) to the relevant channel on [moja global's Slack workspace](mojaglobal.slack.com). 
* If you have other questions, please write to info@moja.global   
  

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://moja.global"><img src="https://avatars1.githubusercontent.com/u/19564969?v=4" width="100px;" alt=""/><br /><sub><b>moja global</b></sub></a><br /><a href="#projectManagement-moja-global" title="Project Management">📆</a></td>
    <td align="center"><a href="http://www.juliancabezas.com"><img src="https://avatars1.githubusercontent.com/u/17553010?v=4" width="100px;" alt=""/><br /><sub><b>Julián Cabezas</b></sub></a><br /><a href="https://github.com/moja-global/GCBM.Chile.Implementation/commits?author=juliancabezas" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!


## Maintainers Reviewers Ambassadors Coaches

The following people are Maintainers Reviewers Ambassadors or Coaches  

<table>
  <tr>
    <td align="center"><a href="http://moja.global"><img src="https://avatars1.githubusercontent.com/u/19564969?v=4" width="100px;" alt=""/><br /><sub><b>moja global</b></sub></a><br /><a href="#projectManagement-moja-global" title="Project Management">📆</a></td>
    <td align="center"><a href="http://www.juliancabezas.com"><img src="https://avatars1.githubusercontent.com/u/17553010?v=4" width="100px;" alt=""/><br /><sub><b>Julián Cabezas</b></sub></a><br /><a href="https://github.com/moja-global/GCBM.Chile.Implementation/commits?author=juliancabezas" title="Code">💻</a></td>
  </tr>
</table>

**Maintainers** review and accept proposed changes  
**Reviewers** check proposed changes before they go to the Maintainers  
**Ambassadors** are available to provide training related to this repository  
**Coaches** are available to provide information to new contributors to this repository  
