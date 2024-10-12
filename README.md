# cc11  
  
## Links of interest:  
  
https://www.postman.com/what-is-an-api/  
https://github.com/rappos/Cat-Facts  
https://catfact.ninja/  
https://owasp.org/API-Security/editions/2023/en/0x11-t10/  
https://portswigger.net/burp/documentation/desktop/tools/intruder/uses/fuzzing  
https://cheatsheetseries.owasp.org/cheatsheets/XML_Security_Cheat_Sheet.html  
https://github.com/arainho/awesome-api-security  
https://github.com/JBAhire/awesome-api-security-essentials  
https://labs.detectify.com/how-to/hack-apis-in-2021/  
https://hackanythingfor.blogspot.com/2020/07/api-testing-checklist.html  
https://github.com/theowni/Damn-Vulnerable-RESTaurant-API-Game  
https://devsec-blog.com/  

##Lab info:

Damn-Vulnerable-RESTaurant-API-Game tips

install Docker desktop  
close Docker desktop - restart Docker desktop with admin rights  

run commands:  
git clone https://github.com/theowni/Damn-Vulnerable-RESTaurant-API-Game.git  
cd Damn-Vulnerable-RESTaurant-API-Game  
./start_app.sh  

Browse to http://localhost:8080/docs#/  

Browse to http://localhost:8080/openapi.json  
Download the json file  

Download and install an API UI tool like Postman or Insomnia  
From Postmand or Insomnia, use the import feature to load in API configs from the openapi.json file  
