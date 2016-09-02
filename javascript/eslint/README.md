# ESLint

[ESLint](http://eslint.org) is one of the most popular Javascript static code analysis tool. 

It can be configured by dropping .eslintrc file in the project root folder. It can also be configured to use different rules for different parts of solution by keeping separate .eslintrc in targetted folders.

There are two configurations here:

1. .eslintrc.json - this file has rules for both code quality and styling
2. .eslintrc_styling.json - this file has only styling rules

Refer to [ESLint Rules](http://eslint.org/docs/rules/) to update configured rules. 

Use rule values 0,1,2 to make sure configuration works with Visual Studio extension:

0 - Off

1 - Warning

2 - Error

## Visual Studio Extension

[Web Analyzer](https://visualstudiogallery.msdn.microsoft.com/6edc26d4-47d8-4987-82ee-7c820d79be1d) is the Visual Studio extension for ESLint. It will apply the configuration in .eslintrc file in the project folder and add violations to ErrorList when a file is saved.