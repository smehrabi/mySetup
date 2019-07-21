# mySetup

Philospophy/guidelines/best practices and config files I like to use to customize my development environment.  

I will also try and keep a list of folks who have inspired some of my decisions.  


## Guidlines
  
Use ESLint.  
Use Prettier.  

### ESLint setup . 
...coming soon.  

### Iterm2 Prefs

I like to title my terminal sessions so I know which is which. You can name the terminal window with the following command:

echo -ne "\033]0;"<Title here>"\007" . 

Replace <Title Here> with your title.  
  
### VS Code Customizations

One of my favorite customization options with VS Code is the ability to change the title bar color. This ability helps me give different colors to each of my editors so that I can quickly identiy which window I need to focus on.

The way I customize that is to add the following to settings.json in my Workbench -> Appearance section where there is an option "Edit in settings.json"

```json
"workbench.colorCustomizations": {
        "titleBar.activeBackground": "#5d43d0"
    }
```

Please not that #5d43d0 is a color option. You can replace that with your own color choice.

