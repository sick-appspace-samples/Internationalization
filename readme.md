## Internationalization
Handling translations to support different languages in the user interface. 
### Description
This sample shows how to prepare translation files and reference these in the user interface to be able to provide the application specific user interface in different languages. 
The language files can be found in pages/i18n. 
For each language a dedicated file must be present with the name in following syntax <language_code>.<optional_identifier>.json. 
For example de.app.json / en.json / es.specificname.json etc.
In the translation files there are key value pairs for each translation which and also allows structuring. The keys must be all lower case. 
The translation noted in the files can the be referenced in the UI-Builder by prepending # and the full structure name.
E.g. #buttons.accept. An example of this can be seen in the page configuration.html in this sample. 

The exception are page names and category names which are used for navigation in the UI, they have a distinct namespace in the language files (page and category). 
In turn page and category names do not need to be prepended with # to be translated.

### How to Run
This sample can be run on the Emulator or on a device. After starting, the user interface can be seen at the DevicePage in AppStudio or by using a web browser.
The language can then be changed in the setting page of the UI.
AppStudio version >= 3.0.0 is required.

### More Information:
See UI-Builder tutorial for more information.

### Topics
System, User-Interface, Sample, SICK-AppSpace
