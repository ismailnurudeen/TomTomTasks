## Task 2:

Develop a basic Android Application with three distinct flavours (F1, F2, F3). The specific content
of the application is not relevant for this task, and should be kept to a minimum, or even empty.
Create a GitHub Actions workflow that automates the building of all APK combinations for each
flavour and build type (Debug/Release). The built binaries should be stored for later retrieval and
usage using a method of your choosing. If all flavour builds are successful, create a new GitHub
release. In the event of unsuccessful builds, store a text file along with the available binaries
indicating "Some builds failed". The workflow can be triggered by events of your choice, such as
pull, push, or workflow_dispatch. The release name can be auto-generated or provided as an input
during workflow_dispatch.

A complete working solution is not required, but a YAML file for discussion purposes is welcome,
even if it includes pseudo-code.

## Solution

I have created an Android app (IceCreamApp) with multiple flavours, F1, F2 and F3 and also a
workflow with actions to build and release different flavour and build type combination for this app. 

See solution in -> [.github](../../.github)
