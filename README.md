# How-to-Recon-for-Bug-Huntung
Credits:- Nahamsec from Youtube.com

Recon is most important step, because tests are only few. We can find many easy/low hanging fruits with recon. E.g. Vulnerable API's.  

Step 1- 
 Noted all in-scope items from hackerone about organization. Here all domains/asset you found are in scope.
Step 2-
 finding all asset is important. Since test is going to go for weeks and we might not find any bug for many days. So noting all end points are imp.
 Tools:
  1. Run amass 
      command = amass enum -d domain_name
      To give domains from file just use amass enum -df file_name. 
  2. Run findomain
      command = findomain -t domain_name
      Note: It is creating error, it will not use API in first go. Only when it gets error on first go then it will use API. 
