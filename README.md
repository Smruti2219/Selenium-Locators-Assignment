Assignment 1 – Basic Locators 

Website: https://opensource-demo.orangehrmlive.com/ 

Tasks: 

- Enter username using ID locator. 
//Id locator not available for the username.
A) driver.findElement(By.xpath("//input[@placeholder='Username")).sendKeys("Smruti S. Samal");

- Enter password using Name locator. 
A) driver.findElement(By.name("password")).sendKeys("New@123");

- Click login button using ClassName.
A) driver.findElement(By.className("oxd-button oxd-button--medium oxd-button--main orangehrm-login-button")).click();

- Count all input elements using TagName. 
A) List<WebElement> inputEles = driver.findElement(By.tagName("input"));
System.out.print("Count all input elements using TagName", +inputEles.size());

