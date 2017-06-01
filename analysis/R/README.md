# R Example Folder

A modular or functional approach to programming can help keep analysis clear, maintainable, and portable to other projects. The utils folder would contain project-specific function definitions, each function trying to accomplish one clear small task that is required for the analysis. Scripts would use something like the following to make those functions available in the main analysis scripts:

```
#Load utility scripts

utility_scripts <- file.path("analysis","R","utils")

for(file in list.files(utility_scripts)){
  source(file.path(utility_scripts,file))
}
```