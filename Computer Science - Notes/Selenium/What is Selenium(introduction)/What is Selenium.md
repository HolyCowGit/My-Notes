# What is Selenium?

**Selenium** is a free (open-source) automated testing framework used to validate web applications across different browsers and platforms. You can use multiple programming languages like Java, C#, Python etc to create Selenium Test Scripts. Testing done using the Selenium testing tool is usually referred to as Selenium Testing.

Selenium Software is not just a single tool but a suite of software, each piece catering to different Selenium QA testing needs of an organization. Here is the list of tools

-   [[Selenium Integrated Development Environment (IDE)]]
-   [[Selenium Remote Control (RC)]]
-   [[WebDriver]]
-   [[Selenium Grid]]

![[SeleniumSuite.webp]]

> 1. Selenium 1 is refered as Selenium RC
> 2. Selenium RC and WebDriver merged together is called [[Selenium 2]] and Improved Selenium 3

## Creators
1. Jason Huggins  ***2004*** - Selenium core
2. Paul Hammant - RC or Selenium 1
3. Patrick Lightbody - Selenium Grid
4. Shinya Kasatani *2006* - Selenium IDE
5. Simon Stewart *2006* - WebDriver



## The Same Origin Policy Issue

**Same Origin policy prohibits JavaScript code from accessing elements from a domain that is different from where it was launched**. Example, the HTML code in www.google.com uses a JavaScript program “randomScript.js”. The same origin policy will only allow randomScript.js to access pages within google.com such as google.com/mail, google.com/login, or google.com/signup. However, it cannot access pages from different sites such as yahoo.com/search or guru99.com because they belong to different domains.

This is the reason why prior to Selenium RC, testers needed to install local copies of both Selenium Core (a JavaScript program) and the web server containing the web application being tested so they would belong to the same domain.

`Very Imp :`

1. [What is Selenium WebDriver? Difference with RC](https://www.guru99.com/introduction-webdriver-comparison-selenium-rc.html)

