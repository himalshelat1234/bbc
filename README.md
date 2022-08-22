
To browse all the test files
1. Unzip the file bbc2.zip
2. Open the folder bbc2/bbc2/
3. Below is a list of folders and what they contain
	Feature - Contains the feature files has the Part1(SpecFlowFeature1.feature) and Part2(SoundsMusic.feature) Scenarios
	Steps - Step definition for the above feature files
	Pages - Class files for the pages being used in the test
	Hooks - For any test setup or breakdown. Currently only using driver.quit
	Utilities - Any files or methods that are widely used can be put here. Currently just defining some constants
	Base - Contains class representing shared data. When we want to share data between different classes. Not used much currently
	


Below are the steps to run the tests. I am using Visual Studio 2019 with netcore3.1
1. Download and install Visual Studio
2. Open Visual Studio -> Open a project or Solution
3. Navigate to the unzipped folder bbc2 and open bbc2.sln
4. Get required packages
	In the Solution explorer - Right click on bbc2 and select Manage Nuget Packages and search and install below packages
		-Selenium.Webddriver 4.4.0
		-SpecFlow.xUnit 3.9.74
		-xunit 2.4.0
		-xunit.runner.visualstudio 2.4.0
		-SeleniumExtras.WaitHelpers 1.0.2
5. Open Test Explorer by clicking on View-Test Explorer
6. Select one or more tests and Run
	
