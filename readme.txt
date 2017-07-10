Webdriver + testng + pagefactory project
repo url: https://github.com/sheetalsingh/WebDriverPageFactory


#How to run framework:
Option 1: command line: single/multiple xml can be given
mvn clean test -DsuiteXmlFile=testng.xml,testngParallel.xml


Option 2: to generate allure reports
mvn clean test site -DsuiteXmlFile=testngWiki.xml
mvn clean test site -DsuiteXmlFile=testngParallel.xml


#Report

todos:
1. Fileseparator, separate all path in one class  - done in branch - "nitin"
2. Reporting - extent
3. Remote server handling
5. image comparison  - try Sikuli
6. email report  - use jenkin


#issues:
0. double logging issue
1. retry listener show skip cases count as well - P3 [maven report show correct result, no skipped cases shown]
2. screenshot for particular id - done (some issue coming, not used in framework)  - P3
