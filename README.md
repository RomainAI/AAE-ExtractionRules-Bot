# AAE-ExtractionRules-Bot
Extraction and creation of clean files from CSV source file

## Description

The main purpose of this bot is to process IQ Bot CSV result file, but logic can apply to any CSV file.

Because our main sales speech is that we offer a solution which doesn’t require technical skills, IQ Bot design and training look good but most documents (if not all) require some cleaning process to get a result. The cleaning process is currently done by creating a task bot in AAE and can be a blocker for some customers, as it looks like a “development tool” / “scripting”. 

The idea of the bot is to provide a ready to use solution, without having to “code” anything in AAE. 

## How to use this bot

Copy "My Docs", "My MetaBots" and "My Tasks" to your local (bot machine) Automation Anywhere folder usually "C:\Users\Username\Documents\Automation Anywhere Files\Automation Anywhere"

Run "Post - Process - IQ Bot.atmx" in "My Tasks" folder, that's it!

## Prerequisites

AA / CR v11.3+

## Available Functions (Metabot) 

* Rename Column Name
* Remove line if field matches regex
* Keep line if field matches regex
* Remove spaces in field value
* Extract regex from field value
* Replace values in field value
* Trim field value
* Format field value
* Lookup in external file

## Documentation

See MS Word document "Extraction Rules - Functions.docx".

## Contributing

First draft a lot can be added, for those who want to add logics feel free, source is in FormatUtility folder (.Net C#)

## Authors

Romain Alexandre - Initial work
