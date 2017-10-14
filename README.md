# Service Oriented Architecture Implementation - Palindrome Web Service (SOAP) # 


1. Just import the zip files using Netbeans (File> Import Project> From ZIP)
2. Do t for both ChowdurySevice and ChowdhuryClient
3. Right click on the ChowdhuryClient project and click Deploy
4. Right click on the ChowdhuryClient project and click run
5. The client programme will open in your default web browser


### Disclaimer: ###
The programme works on its own. Problem starts when we enter a WSDL URL which has different java class and package name. I doubt that the sending the string to newURL using the variables and package name such as com.palindrome will let us use the service on other URLs. All the web services then need to have the same implementation class names. In this project its com.palindrome.PalindromeCheck.





