# Tibor's Davinci Resolve scripts

## Context
There are two main types of scripts in Davinci Resolve: 
* Resolve scripts which act on a project
* Fusion scripts, which are designed to act on the comp level 

If you need help with Fusion scripts, you can consult the [Fusion Scripting Guide](https://documents.blackmagicdesign.com/UserManuals/Fusion8_Scripting_Guide.pdf). For Resolve scripts, you can refer to this [documentation](https://diop.github.io/davinci-resolve-api/#/?id=using-a-script).

Notes:
* Some features might be restricted in the free version of Resolve.
* The console can be used to execute commands and scripts, with both lua and python languages supported.
* This document focuses exclusively on using Davinci Resolve on MacOS


```
Scripts location:
/Users/tudvari/Library/Application Support/Blackmagic Design/DaVinci Resolve/Fusion/Scripts

Env variables to include in .zshrc for example
RESOLVE_SCRIPT_API="/Library/Application Support/Blackmagic Design/DaVinci Resolve/Developer/Scripting/"
RESOLVE_SCRIPT_LIB="/Applications/DaVinci Resolve/DaVinci Resolve.app/Contents/Libraries/Fusion/fusionscript.so"
PYTHONPATH="$PYTHONPATH:$RESOLVE_SCRIPT_API/Modules/"
```
