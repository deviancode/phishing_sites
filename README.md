# Phishing_sites

The format of the xml file is the following:

```
<?xml version="1.0" encoding="UTF-8"?>  
<report>  
  <threat>   
    <category></category>  <!-- phishing/scam/bec/.. -->  
    <scheme></scheme>  <!-- http/https/ftp/.. -->  
    <host></host> <!-- The host -->    
    <path></path> <!-- The path itself -->  
    <query></query> <!-- If ? query was use -->  
    <query_format></query_format>  <!-- which query format email/base64 encoded email/.. -->  
    <fragment></fragment> <!-- If # fragment was used -->  
    <compromised></compromised>  <!-- dedicated service or open-up server -->  
    <detected_year></detected_year> <!-- Year detected -->  
    <detected_month></detected_month> <!-- Month detected -->  
    <detected_day></detected_day> <!-- Day detected -->     
    <reported></reported>  <!-- yes/no netcraft and phishtank -->  
    <closed></closed> <!-- For follow up, when removed or not reachable anymore -->  
    <trarget></target> <!-- Targeted customers, like Microsoft or general -->  
    <language></language> <!-- which audience is targeted based on language -->  
  </threat>  
</report>  
```
