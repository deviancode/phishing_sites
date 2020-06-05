# Phishing_sites

The format of the xml file is the following:
Example:
```
<?xml version="1.0" encoding="UTF-8"?>  
<report>  
  <threat>   
    <category>phishing</category>  <!-- phishing/scam/bec/.. -->  
    <scheme>https</scheme>  <!-- http/https/ftp/.. -->  
    <host>qwerty.foo.bar</host> <!-- The host -->    
    <path>/foobar</path> <!-- The path itself -->  
    <query>?email</query> <!-- If ? query was use -->  
    <query_format>base64 encoded email</query_format>  <!-- which query format email/base64 encoded email/.. -->  
    <fragment></fragment> <!-- If # fragment was used -->  
    <compromised>yes</compromised>  <!-- dedicated service or open-up server -->  
    <detected_year>2001</detected_year> <!-- Year detected -->  
    <detected_month>01</detected_month> <!-- Month detected -->  
    <detected_day>01</detected_day> <!-- Day detected -->     
    <reported>yes</reported>  <!-- yes/no netcraft and phishtank -->  
    <closed>yes</closed> <!-- For follow up, when removed or not reachable anymore -->  
    <trarget>foobar</target> <!-- Targeted customers, like Microsoft or general -->  
    <language>english</language> <!-- which audience is targeted based on language -->  
  </threat>  
</report>  
```
