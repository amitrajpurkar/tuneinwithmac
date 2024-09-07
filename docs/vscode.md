==```to be documented```==

 * vs-code settings [by CJ](https://github.com/CodingGarden/vscode-settings)
 * open vscode 
 * Cmd + Space (start raycast) type “code“ enter
 * from terminal type “code” enter
 * Cmd + , (command, comma) to open settings 
   * from here you can use the ui to select different configurations 
   * alternatively from vscode press Cmd Shift P and type settings.json, select option “edit settings.json” - this opens the user’s settings json for customising settings 
     * you can refer to default/settings.json to see what options or choices you have; note that the default settings file is read-only; so add your customizations and tweaks to user/settings.json
 * note that the main settings json (default settings) is included in application installation 


### Noteworthy settings
here are a few: 
```json
{
    "workbench.sideBar.location":"right",
    "editor.minimap.autohide": true,
    "editor.linkedEditing":true,
    "workbench.editor.showTabs":"none"
}
```


 ### handy extensions
 some extensions help with productivity boost
 * note that Microsoft owns VS Code.. so extensions from them should be first choice
 * auto Hide is one such
 * Markdown is what you typically use for documentation
   * Markdown Preview
   * Markdown to PDF ??
 * Prettier: code formatter; one must have
 * if you want to work on Java, one options is a vscode installation with Java Pack for IOS or Windows
 * since as a developer we typically work as polygot programmer, sticking to one installation per programming language may not be ideal -- this varies from programer to programer by individual taste
 * Java related extenstions
   * Language Support for Java from Redhat
   * Debugger for java from Microsoft
   * Test runner for Java from Microsoft
   * Spring Boot Extension pack from VMWare (includes Spring Boot Dashboard, Spring Boot Tools, Spring Initializer)
   * Gradle for Java from Microsoft
   * Java platform extension frorm Oracle (you may not use this, if using the one from Redhat)
 * Python related extentions
   * Python language support from Microsoft
   * Python debugger extension from Microsoft
   * Pylance from Microsoft
 * Codeium -- excellent pair-programmer AI-bot for coding
   * you will need login for using Codeium and its free for Individual use.
