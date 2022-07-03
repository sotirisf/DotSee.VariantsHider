# DotSee.VariantsHider
This is a simple plugin for Umbraco v9.4+ which hides variants in the back office content tree that have not been created yet (the ones that appear as placeholders with parentheses around them). 
It also adds a new menu option to the "Content" context menu allowing you to toggle between displaying and hiding said variants.

The purpose of the plugin is to unclutter the content tree for editors in case there are too many unset variants between languages. It is based on the current back office UI and CSS, and it's possible that it'll break if changes are made there.

After installing the plugin, you can enable it by adding the following in appsettings.json:

```
 "VariantsHider": {
   "Enabled": true,
   "Caption":  "My menu caption"
 }
 ```
 
 Caption is optional, and you can omit it - a default caption will be displayed. Otherwise, set it to what you like it to say, e.g. "Unclutter me!".
 
<img width="217" alt="image" src="https://user-images.githubusercontent.com/1838996/177052861-320c7af4-0f41-4807-95be-5bbcdca5810f.png">

Before hiding unset variants:

<img width="251" alt="image" src="https://user-images.githubusercontent.com/1838996/177052891-a98c4912-650b-4243-b8ec-04a6f0fbe279.png">

After hiding unset variants:

<img width="221" alt="image" src="https://user-images.githubusercontent.com/1838996/177052903-5e18cb2f-2d7b-4f5a-b073-11802c11b430.png">

