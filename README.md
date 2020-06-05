# Phishing_sites

The format of the json file is the following:
Example:
```
{"threat":[
  { "category":"", "scheme":"", "host":"", "path":"", "query":"", "query_format":"", "fragment":"", "compromised":"", "detected_year":"", "detected_month":"", "detected_day":"", "reported":"", "closed":"","target":"", "language":"" },
{ "category":"", "scheme":"", "host":"", "path":"", "query":"", "query_format":"", "fragment":"", "compromised":"", "detected_year":"", "detected_month":"", "detected_day":"", "reported":"", "closed":"","target":"", "language":"" }
]}
```
   
category -> phishing/scam/bec/..  
scheme -> http/https/..  
host -> The host = fo.ob.ar  
path -> The path = /foo/bar/  
query -> if ? query was use = ?email  
query_format -> which query format email/base64 encoded email/..  
fragment -> If # fragment was used  
compromised -> simple yes or no = dedicated service or open-up server  
detected_year -> Year detected  
detected_month -> Month detected    
detected_day -> Day detected  
reported -> yes/no netcraft / phishtank / microsoft   
closed -> For follow up, when removed or not reachable anymore  
target -> Targeted customers, like Microsoft or general
language -> which audience is targeted based on language  

