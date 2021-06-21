# Waters(TM) Patrol(TM) UPLC(TM) Report Parser

This plugin parses report files output from Waters(TM) Patrol(TM) program to 
extract the concentration of an analyte. The plugin will average the results 
of three injections before reporting a new concentration value to Rxn Rover.
A sample report is included with the plugin, whose format must be matched 
exactly for the parser to work.

**Note:** The Waters, Patrol, UPLC trademarks are owned by Waters Corporation 
and its affiliated entities.

## Installation

Download this plugin by clicking the "Code" button in the top right of its 
GitHub repository and selecting "Download ZIP". Extract the ZIP file into your 
`<documents>/Plugins/Analyzers` directory to finish installation. Create the 
`Analyzers` subdirectory if it does not already exist.