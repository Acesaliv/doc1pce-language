# doc1pce-language
Visual Studio Code extension for doc1pce language syntax highlighting.

# How-to Intall
Copy the contents of this project in a subfolder of vsc extensions folder. (in windows this is c:\users\username\.vscode\extensions)

# Recomended extensions
It is recomended also to install the "CodeMap" Extension (https://marketplace.visualstudio.com/items?itemName=oleg-shilo.codemap) and configure a user defined syntax in "settings.json" to identify list of procedures:

    "codemap.src": [
        {
          "pattern": "begin procedure <\\w+>",
          "clear": "begin procedure",
          "icon": "function"
        }
    ],

 
