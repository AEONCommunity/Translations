## How-to translate the website files

First, you need to clone the Aeon.cash website
```
git clone --recursive https://github.com/aeonix/aeonix.github.io
```

Inside that folder, you need to modify and add some files before they are added to the main translations
repository. Here are the files that you need to modify for translating the website:

* _config.yml
  -This file contains the bulk of the translations
  -Under each title, you need to add in your two-letter language abbreviation along with the translation
    An example would be `` rs: "text that is translated between the quotes" `` for Russian. Make sure that
    every line that has had a translation performed with the changes already has a new tag for your language. 
    Make sure to follow the same formatting as the lines above using correct characters such as < or / or ".
    
* index.es.html
  -You need to copy-paste one of the index files and add your language tag in the name of the file and then
  in the file you need to change the tag inside to match all other tags in the config.yml file you added. 
  -Example: if the file name was index.es.html you need to copy paste that file and rename to index.rs.html.
  Inside that file, you need to change the ``lang: es`` to ``lang: rs`` if adding Russian.
  
* header.html
  -In this file you need to add you language tag to a new line for the dropdown tile at the bottom. 
  -Example: copy the line ``<a href="/index.eo">Esperanto</a>`` and add a new line as 
  ``<a href="/index.rs">Russian</a>`` to add Russian as an option in the language selector dropdown.
  

Adding the files to the Translations repo:

Once your changes have been made to the documents, create your own folder in our repository under your language
name and add the files. Don't forget to add a contributing.md file to your folder and also modify the main 
contributing file as needed. 
