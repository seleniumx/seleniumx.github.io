![Image](https://raw.githubusercontent.com/seleniumx/seleniumx/master/Seleniumx_logo.png)

## Welcome to Seleniumx

Seleniumx is a test automation framework developed based on Selenium. QA/Automation Engineers who are developing automated test cases more familiar with selenium functionalities and features. But it is hard to follow a common framework who can understand and used by every team member. As a solution, we developed a common framework that is no need to build from scratch, but also the frame implemented for you. You don't have to worry about what kind of OS you are using or what kind of browser type you using because of each and every component built-in with Seleniumx. You just need to call an annotation and that's all. All the things will be done by Seleniumx for you.

Organization : [Seleniumx](https://github.com/seleniumx/seleniumx)

### Supported OS types 
- MAC OS
- Windows
- Linux


### Latest version
Seleniumx 1.0-SNAPSHOT

Maven Dependencies
```
<dependency>
  <groupId>org.seleniumx</groupId>
  <artifactId>seleniumx</artifactId>
  <version>1.0-SNAPSHOT</version>
  <classifier>jar-with-dependencies</classifier>
</dependency>
```

### Steps to implement the framework with your test environment
- Extend the Start class with tour test case class
- Implement the annotation and give parameters accordingly

E.g:
```
public class TestClass extends Driver {
    @DriverSettings
    @Test
    public static void sdsf() {
    }
}
```
### Supported Annotations 

- @DriverSettings
Put the annotation before the method declaration. 
```
    @DriverSettings(
               OS = DriverSet.OS.LINUX,
               WINDOW_SIZE = DriverSet.WINDOW_SIZE.DEFAULT,
               BASE_URL = "https://www.samplewebsite.com",
               IMPLICIT_WAIT = 100
    )
```


