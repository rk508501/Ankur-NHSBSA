# Pre-requisites:
### <sub>- Java JDK 1.8 or above</sub>
### <sub>- Maven (Any version)</sub>
### <sub>- Set the Maven home path(Check the maven version while executing "mvn -v" in the cmd)</sub>

# Description : 
### <sub>This UI automation framework is intended to automate various test sceanrios that cover permutations of the patient choices in order to check the eligibility for the health coverage. The test simulate the options made by the user and tally the result against the expected test data. With the cucumber library, it becomes easy to go through the business scenarios and verify the outcome for the given sets of input data. </sub>
  
# UI Automation for the NHS Cost Checker Tool
### <sub>An Automated Solution that validates user get a result of whether he/she can get help or not with their NHS costs.</sub>

# Framework Overview: 
### <sub>- This is a Java/Maven based project that utilized Selenium WebDriver library for the UI navigation. Use Selenium-Java to navigate to url https://services.nhsbsa.nhs.uk/check-for-help-paying-nhs-costs/start and on basis of entered circumstances into the checker tool and fetched the help result.</sub> 
### <sub>- Cucumber is used for the Behavior Driven Development. Used Page object model approach and the assertions are made with the Junit.</sub>

# Local Execution Steps:
### <sub>1. Create a project folder in your local.</sub>
### <sub>2. Navigate to project folder/dir and open cmd.</sub>
### <sub>3. Run the command : git clone https://github.com/Ankur1Dhingra/Ankur-NHSBSA</sub>
### <sub>4. After cloning the project successfully in the local, then navigate to project folder/dir where pom.xml is present and open cmd and Run the command : mvn clean verify</sub>
### <sub>5. You can see the different reports under the folder : </sub>
#####<sub>      a. target -> cucumber-JVM-reports ->cucumber-html-reports -> feature-overview.html</sub>
##### <sub>     b. target -> cucumber-JVM-reports ->cucumber-html-reports -> file-src-test-resources-Features-cost-feature.html</sub>
##### <sub>     b. SparkReports -> sparkreport.html</sub>

### **Make sure maven home is set correctly and mvn command is executed from correct project dir having pom.xml.(where you import your project)

