
# All images
(displayed with a dataview query)
```dataviewjs 
const pathToImageFolder = '_Assets/Images' 
const imageFiles = app.vault.getFiles().filter(file => file.extension == 'png' && file.parent.path === pathToImageFolder) 

imageFiles.forEach(file => dv.paragraph(`![[${file.path}|profile left lp]]`)) 

 ```

