# XML_Resources_Modifier
It searches through project files ( .NET Core  ==> .cs &amp; .cshtml &amp; .config) and remove useless tags in resource file.

- Generates new xml file.
- Make new text file named RemovedTags that contains list of _removed tags_.
- Make new text file named FoundTagsFile that contains list of _found tags_.

*Note: Generated files located in application directory (XML_Modifier.py)*

## Usage
Set your project path and XML file path in these variables like this :


```python

projectPath = 'C:\\Users\\{Username}\\Desktop\\{Project name}'
xmlFilePath = 'C:\\Users\\{Username}\\Desktop\\{Project name}\\{XML file}'
