## Flame SIEM Pipeline

Flame is a SIEM integration tool that enables security professionals to import scanner vulnerability reports into popular SIEMs. 

https://github.com/blazeinfosec/Flame

This project allows Flame to be integrated into a Gitlab CI/CD pipeline for complete automation.


## Installation

Clone or copy the .gitlab-ci.yml file into your Gitlab repository.

```
git clone https://github.com/jamesbower/Flame_SIEM_Pipeline
```
## Dependencies

In order for this to work, make sure your Gitlab runners and project are setup correctly. You will also need to modify the .gitlab-ci.yml to include your proper SIEM credientials.
