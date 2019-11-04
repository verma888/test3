# test3


Manual :
5.Smoketesting:during releasing the time of an application or any software the test engineer do one round of smoke testing to ensure that all the fields of this application like critical,major,mandatory fields are working fine or not . It is  a positive flow of testing where we will check both newly added feature and also old feature.

4.Scenario for placing  order in flipkart:
Scenario1:Enter the URL www.flipkart.com
Scenario2:Enter the valid user name
Scenario3:Enter the valid password
Scenario3:Click on the login button.
Scenario4: Go to your order Page
Scenario5:find out your order and click on buy now option
Scenario6:Click on COD option
Scenario7:Click on Place order Option
Scenario8:Enter the 3 digit number showing above in a box
Scenario9:Click on place order option.
Scenario10:Succesfully order placed

3.High Priority example: Suppose am taking the example of www.google.com
While updating this site by mistakely one letter “o” is missed.
That time updating the wrong company logo is the first  priority option ok but its just a spelling mistake/missing a letter that time its low severity option.

2.Login Scenario:
Scenario1:Enter the URL www.gmail.com
Scenario2:Enter the valid user name
Scenario3:Enter the valid password.
Scenario4:Click on login button.
Scenario5:successfully Gmail page logged 
Scenario6:Go to your account and clicked on sign out option
Scenario7:Accont successfully logged out
1:Mailing Inbox scenario:
Scenario1:Enetr the URL www.gmail.com
Secnario2:Enter the valid user name
Scenario3:Enter the valid password
Scenario4:Click on login button
Scenario5:click on Inbox Option
Scenario6:Inbox page successfully opened.

Corejva:

1:Class A;
Public static void main (String args[]);
{
for(int i=0; i<=5; i++)
for(int j=I;J<=5:J--)
System .out. Print ln(j);
}
2.Class B;
Public static void main (Stringargs[]);
{
String S1 = “java”;
System. out. Print ln(S1.Chart at(“a”));
}

3.Reverse a string:
String S1 =”Test Data”
Int size = S1.lenth();
String reverse=” _”
For(int i=size-1;i>=0;i--);
System. out. Print ln(reverse+s1.charAt(i)));
Selenium:
Selenium:
1:           Class Handling Multiple Windows;
              Public Static Void main (String []args);
               Web driver driver = new firefox Driver();
               Driver. get(“URL”);
               Set windows id=driver. get window Handles();
               System. out. Print ln (“windowsid”);
               Object[] data=windowsid. toArray();
               System. out. Print ln(data[0]);
It will print staring from 0 index.Then it will print [1] like this only

2.Implicitly Wait:
It will wait for the fields during excutuion of test script within specific time duration
Syntax: driver. manage. timeout. implicitlywait (20,Timeuit.SECONDS);
Explicitly Wait:
It will wait for particular fields of your choice within a specific time duration.
Syntax:web driver wait(20,drvier);

3.For any kind of mouse movement operation we have to use Action Class and we have to create
A reference variable of Action Class
Actions action = new Acrions(driver);
Action.MoveToElement(driver.findelement(By.xpath(“xpath”))).click();

4.Taking a screenshot in selenium we will use driver.getScreenShotAs(); method

5.list<>web element linkslist=driver.find Elements(By.Tagname(“a”));
System.out.Println(“links list.size());
   
