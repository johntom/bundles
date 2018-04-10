Steps requored to add plugin to FEC
1. au new (take all defaults)
2. au install  aurelia-toolbelt
Under the bundles section of the file, copy and paste the following:
{
 {
        "name": "aurelia-toolbelt.js",
        "dependencies": [
          {
            "name": "aurelia-toolbelt",
            "main": "aurelia-toolbelt",
            "path": "../node_modules/aurelia-toolbelt/dist/amd",
            "resources": []
          }
        ]
      },
3. au build --env prod
4. C:\Frameworks\Frontend\plugin\ FECPlugin\scripts\aurelia-toolbelt.js
to 
5. bundles\aurelia-toolbelt
6 see ref in main.js aurelia-toolbelt