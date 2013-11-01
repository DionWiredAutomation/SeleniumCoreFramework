SeleniumCoreFramework
=====================

This is an extract of the 'Core' Cucumber Selenium Framework for DionWired Automation Project
 +as of October 2013. In theory all the necessary source files are avaliable to build
 +this using Maven. However it's primarily provided as a reference, and should not be
 +outright used on a new project without consultation.
 +
 +As a quick list of what this code comprises:
 +
 +- Java based wrappers for the core Selenium driver
 +- A similar wrapper for Sikuli-API, allowing interop with the WebDriver instance
 +- A custom test reporter, and a JUnit test to
 + create a report based on that output
 +- Some common 'Custom Controls' for Selenium
 +
 +This file does not contain any of the feature files, step definitions, page objects
 +or glue code which would be necessary to actually execute any tests. These should
 +be implemented on a per-project basis.
 +
 +For further details, please contact SQS India Dionwired Automation Team
check this, is this detail ok to put in git readme?
