# Web-scraping-company-information-with-selenium-python
In this study, I will utilize a list of tax IDs from Vietnamese companies to search for and extract various pieces of information. This includes details such as the company's address, name, business entity, industry, phone number, representative, the source link, and its operational status. All data will be gathered from masothue.com.


I have attached a crawldata file that contains empty fields. The extracted business information will be saved into these fields: company, industry, business entity, representative, phone number, status, address, and source link.

To begin, I will install the necessary libraries for this project, specifically Selenium and WebDriver Manager. 

***VERY IMPORTANT: It’s important to ensure that the code file for this project is located in the same directory as your crawldata file. You can find the current directory of your project by executing the following code:***

    import os
    current_directory = os.getcwd()
    print("Current path of this project:", current_directory)

