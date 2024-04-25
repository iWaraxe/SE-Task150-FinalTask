# Task 150. Final task
Please complete the final task of the training.


[AUT](https://magento.softwaretestingboard.com/)
There are 5 scenarios with steps and expected results in the end. It doesn’t mean that you will have 5 auto-tests. You can decide by yourself how many auto-tests you must implement to cover all scenarios.


## AP-1 Verify the ability to create an account
1. Go to [the login page](https://magento.softwaretestingboard.com/customer/account/create/)
2. Fill required fields
3. Click the Create an Account button  
   Expected result: An account was created


## AP-2 Verify the ability to log in to the account
1. Go to main page: https://magento.softwaretestingboard.com/
2. Fill Email address and Password inputs
3. Click Sign in button  
   Expected result: You was able to login


## AP-3 Verify the ability to add address
1. Login
2. Go to address book:https://magento.softwaretestingboard.com/customer/address/index/
3. Add new address
   Expected result: New address was added to the address list


## AP-4 Verify the ability to add to Wishlist
1. Login
2. Go to page with clothes
3. Go to any product detail page and click Add to Wishlist button  
   Expected result: Product was added to Wishlist


## AP-5 Verify the ability to add to cart
1. Login
2. Go to page with clothes
3. Add 3 different products to cart
4. Go to cart  
   Expected result: All 3 products are in the cart and subtotal is correct


## Technology stack
- Programming language – Java
- Build and project management tool – Maven or Gradle
- Testing framework – JUnit5
- Browser Automation – Selenium WebDriver
- Reporting –  framework

## Tasks
- Automate 5 scenarios, which are described above
- Tests from one test class should be executed in one browser (if 3 test classes – browser should be opened 3 times, before each test class, not before each test method)
- Required patterns: Page Object (Page Factory), Singleton, Strategy (You can add more, if needed)
- If your project uses DDT - store datasets in txt/xml/json files
- Project should be placed on GitHub or Bitbucket
- Tests should work in Chrome and Firefox
- Add switch in your code to run tests locally/ using Selenium Grid/SauceLabs/Docker (user can give params – url, port, etc.)
- If some tests fail, attach screenshot, date and time, browser, platform version to your report
- Add cleanup
