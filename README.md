# Easily Understand Page object model [POM]

Using page object model eliminate the duplicate test code.
# How to create a POM  [Follow the steps]
Here i am explaining simple test cases run by using POM
In Eclipse create one java project name it as abcd.
create a package xyz
create a 3 class like this

# Here class name is Login
1)In one class save all page object element in one page like this

public static webelement username(Webdriver driver)
{
return driver.findelement(by.xpath(""));
}


# Create a second class like this.
In second class we call the objects.

class name+Webelement name .In this case 1st class name is LOGIN  

Login.username(driver).sendkeys("");

3)Now call the 





 
