## Extract JIRA project structure

This will be run only once.


### S-JQL
roots = issue in structure(${structureName}, 'root' )
children = issue in structure(${structureName}, 'parent in ${ISS}'  )


### ALT1. export form JIRA - SELECTED
https://confluence.atlassian.com/jiracoreserver073/working-with-search-results-861257284.html
- csv
- xml

Q: how to export parent/sub-item relation ?

A: Structure view  > index 
- export excel > csv



### ALT2. use jira-python api

issue: needs security set-up


