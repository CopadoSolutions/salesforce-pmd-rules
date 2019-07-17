# salesforce-pmd-rules [![Build Status](https://travis-ci.org/CopadoSolutions/salesforce-pmd-rules.svg?branch=master)](https://travis-ci.org/CopadoSolutions/salesforce-pmd-rules)
This repository contains custom rules developed by Copado customers to extend Salesforce PMD default rules.

### Table of Contents
* [Project Configuration](#project-configuration)
* [Adding Custom Rules](#adding-custom-rules)
* [All Custom Rules](#all-custom-rules)
* [Next Steps](#next-steps)



### Project Configuration
Clone this repository and configure the project as a Maven project either importing it to your preferred IDE or using the Maven command line interface. 

### Adding Custom Rules
1. Fork this GitHub project and create a new branch out of master where the rule will be implemented. The naming convention for the branch is **rules/{company-name}**. Note that the master branch of the forked project must be up to date with the parent project before creating the new branch. If you are working with a previously forked project ensure master branch is up to date (best practice is to remove the fork once the Pull Request is closed and create a new one for the next request)

2. Implement the rule java class directly in the **copado.pmd.rules** package. The java class should be named with the custom rule name (**Custom_Rule_Name.java**).

3. Write test classes to cover the implemented rule code (in **test/java/copado.pmd.rules** package).

3. Update the README to add the new rule to the [All Custom Rules](#all-custom-rules) table.

4. Create a Pull Request to master branch.

### All Custom Rules
| Rule Name | Rule Description | Source (Company Name)| 
| --- | --- | --- | 

### Next Steps
To use within Copado any custom rule from the [All Custom Rules](#all-custom-rules) table use the following instructions:
https://docs.copa.do/article/89r0hif9tw-custom-pmd-rules-for-static-code-analysis

