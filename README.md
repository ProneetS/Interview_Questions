# Interview_Questions

<u> ********Most Asked Interview Questions******* </u>
1. Write a java program for the largest number from three number
2. What is SDLC and STLC? And Explain its phases.
3. Define your roles and responsibility.
4. What is regression testing?
5. What are different methodologies of SDLC? Explain each.
6. Define Agile?
7. Define Scrum And Sprint?
8. What is the estimation in Sprint?
9. What is sprint backlog?
10. What are the different reports in Testing?
11. What are the key components of the Test Case report?
12. What are the components of a defect report?
13. What is Jira?
14. How do you log defect in Jira?
15. How do you link bugs with the user story?
16. What is sprint?
17. Define black box and white box testing,
18. Define functional testing.
19. Define the oops concept in java.
20. Give me examples of oops which you used in your framework.
21. What is TestNG
22. What is usability testing?
23. What are the steps for reporting the defect in Jira?
24. Define Structure of Selenium?
25. How will you handle the dropdown in selenium?
26. Different types of wait in selenium? Explain each of them.
27. Difference between hard and soft assertion?
28. Why are we using "WebDriver driver = new ChromeDrive ()"? 
Why can't we write RemoteDriver driver = new ChromeDrive();
29. Explain the different Annotation in TestNG?
30. Define Priority and Severity of the Bug?
31. How to maximize the screen in Selenium?
32. What are the different closure reports?
33. What is the difference between a Test Plan and a Test Strategy document?
34. Define Bug lifecycle of JIRA.

    
</br>
</br>


********Mostly Asked Selenium Interview Questions*******

1. What is Selenium?
→ Selenium is an open-source automation testing tool designed for web application testing.

2. Explain different Selenium components.
→Selenium WebDriver, Selenium IDE, and Selenium Grid are the main components.

3. What is Selenium WebDriver?
→ Selenium WebDriver is a web automation framework that allows you to interact with web elements and perform actions on web applications.

4. How do you locate elements in Selenium WebDriver?
→ Elements can be located using methods like ID, Name, XPath, CSS Selectors, and more.

5. What is the difference between findElement() and findElements() in Selenium?
→findElement() is used to identify a single element present in a webpage whereas findElements() is used to identify multiple elements present in a window. findElement() returns the first matching element, while findElements() returns a list of all matching elements.

6. What is a WebElement in Selenium?
→ A WebElement is an interface in Selenium that represents an HTML element on a web page.

7. Explain the difference between Implicit Wait and Explicit Wait.
→Implicit Wait sets a global timeout for all elements, while Explicit Wait is applied to specific elements with a custom timeout.

8. What is the Page Object Model (POM) in Selenium?
→POM is a design pattern that helps to create an object repository for web elements.POM improves code readability and reusability. It helps to reduce code duplication and improves test case maintenance.

9. How do you handle pop-up windows in Selenium?
→ You can use the switch To method to handle pop-up windows, alert boxes, and frames.

10. What is TestNG, and why is it used in Selenium?
→TestNG is an automation testing framework that facilitates test configuration, parallel execution, and reporting in Selenium.

11. Explain the difference between driver.get() and driver.navigate().to()?
→Both methods navigate to a URL, but driver.navigate().to() allows for forward and backward navigation within the browser history.

12. How can you simulate mouse actions in Selenium?
→ Actions class in Selenium is used to simulate mouse actions like click, drag and drop, and context-click.

13. What is the purpose of the Selenium Grid?
→Selenium Grid is used for parallel test execution on multiple machines and browsers.

14. Explain the difference between driver.close() and driver.quit)?
→driver.close() closes the current browser window while driver.quit() closes the entire browser session.

15. What is Apache POI?
→Apache POI is the most popular Java library/API used to interact with Microsoft Excel Sheets. It is used to read data from Excel sheets and write data into Excel sheets.


</br>
</br>


********Interview questions series for QA Automation Role*******

Experience level -> 3 to 8 years 
Duration -> 1.5 hrs.
Quick tips - good understanding of programming, QA and Selenium

Questions:

1) Brief me about your experience 
2) What tools and technologies have you worked on? 
3) What’s your favorite programming language? And rate yourself

Note - If you rate yourself 6 or above then get ready to face challenging coding questions.

4) Find the longest substrings of these three strings: 
Example 1 - aab
Example 2 - pwwkew
Example 3 - abcbcabcda

5) Have you created a dynamic Xpath? If yes then give examples. 
How to automate the elements which sometimes pass or fail?
6) How to send only lowercase text where data is derived from external source, without using any java functions or libraries.
7) What is the difference in keyword driven vs data driven vs behavior driven frameworks?
8) What is Hashmap? 
9) If hashmap is available then why do you need HashSet?
10) How to handle exceptions? 
11) Why do you need finally block? 
12) Why do you use Array when ArrayList is available?
13) What are different ways to execute parallel tests in selenium? 
14) How to execute different suites using Maven and TestNG? 
15) Create a dynamic XPath which can find all headlines on Amazon.com 
Steps - 
Go to Amazon.com
Search for Smart TV
Create Xpath to retrieve the name of all products and store in List
16) Why strings are immutable? 
 17) What is string constant pool? 
 18) When int a = 20; 
int b = a ; 
System.out.println(a); -> o/p - 20
System.out.println(b); -> o/p - 20
a=30; 
System.out.println(a); -> o/p - 30
System.out.println(b); -> o/p - 20

But when we do same operation in HashMaps

Map<String, Integer> map1 = new HashMap<>();
map1.put(“value”, 25);

Map<String, Integer> map2 = new HashMap<>();

map1=map2;

System.out.println(map1); -> o/p - value,25
System.out.println(map2); -> o/p - 20 - value,25

Now if we update this to - 
map1.put(“value”, 42)

System.out.println(map1); -> o/p - value,42
System.out.println(map2); -> o/p - 20 - value,42

Why does this happen??

19) Why do you need Throw and Throws keyword when we have Try,catch and finally? 
20) Explain Smoke vs Sanity vs Regression differences? 
21) What do you understand by git rebase?

