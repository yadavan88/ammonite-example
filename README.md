# Sample Ammonite Script #

For learning

- Downloads a file using upicke
- Parse the JSON contents of the file
- Filter country by input value for the continent
- Write the filtered content as JSON file using amm-ops


How to execute?
`amm downloader.sc AS` -- Filter for countries in ASIA 

Prerequisite
- Need Ammonite 2.2.0
- For newer versions, need to change the code `@doc("Pass continent code")` to `@args(doc="Pass continent code")` 
- Can use coursier to install and manage ammonite. Coursier cheatsheet available [here](https://github.com/yadavan88/coursier-cheatsheets) 
