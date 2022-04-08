### 1. 10 minutes School
~~~
https://ali-abdullah.ml/APIS/10min?number=01xxxxxxxxx 

https://ali-abdullah.ml/APIS/10min1?number=01xxxxxxxxx
~~~
### 2. Agora Superstore
~~~
https://ali-abdullah.ml/APIS/agora?number=01xxxxxxxxx
~~~
### 3. Alesha Superstore
~~~
https://ali-abdullah.ml/APIS/alesha?number=01xxxxxxxxx
~~~
### 4. Arogga Pharma
~~~
https://ali-abdullah.ml/APIS/arogga?number=01xxxxxxxxx
~~~
### 5. Binge Buzz
~~~
https://ali-abdullah.ml/APIS/bin?number=01xxxxxxxxx
~~~
### 6. Bioscope
~~~
https://ali-abdullah.ml/APIS/bio?number=01xxxxxxxxx
~~~
### 7. Byju's
~~~
https://ali-abdullah.ml/APIS/byj?number=01xxxxxxxxx
~~~
### 8. Chine Spot
~~~
https://ali-abdullah.ml/APIS/cine?number=01xxxxxxxxx
~~~
### 9. Circle Robi
~~~
https://ali-abdullah.ml/APIS/circle?number=01xxxxxxxxx
~~~
### 10. Daktar Bhai
~~~
https://ali-abdullah.ml/APIS/daktar?number=01xxxxxxxxx
~~~
### 11. Easylife Bd
~~~
https://ali-abdullah.ml/APIS/easy?number=01xxxxxxxxx
~~~
### 12. Fundesh
~~~
https://ali-abdullah.ml/APIS/fun?number=01xxxxxxxxx

https://ali-abdullah.ml/APIS/fun1?number=01xxxxxxxxx
~~~
### 13. Groori
~~~
https://ali-abdullah.ml/APIS/ghoori?number=01xxxxxxxxx

https://ali-abdullah.ml/APIS/ghoori1?number=01xxxxxxxxx
~~~
### 14. Health Plus
~~~
https://ali-abdullah.ml/APIS/health?number=01xxxxxxxxx
~~~
### 15. Hungry Naki
~~~
https://ali-abdullah.ml/APIS/hungry?number=01xxxxxxxxx
~~~
### 16. Iqra Care
~~~
https://ali-abdullah.ml/APIS/iqra?number=01xxxxxxxxx
~~~
### 17. Jachai Store
~~~
https://ali-abdullah.ml/APIS/jachai?number=01xxxxxxxxx
~~~
### 18. Market Bangla Store
~~~
https://ali-abdullah.ml/APIS/market?number=01xxxxxxxxx
~~~
### 19. Paikaree Store
~~~
https://ali-abdullah.ml/APIS/paikare?number=01xxxxxxxxx
~~~
### 20. Picabo Store
~~~
https://ali-abdullah.ml/APIS/picabo?number=01xxxxxxxxx
~~~
### 21. Quiz Giri
~~~
https://ali-abdullah.ml/APIS/quiz?number=01xxxxxxxxx
~~~
### 22. Red X
~~~
https://ali-abdullah.ml/APIS/redx?number=01xxxxxxxxx
~~~
### 23. Swap Shoping
~~~
https://ali-abdullah.ml/APIS/swap?number=01xxxxxxxxx
~~~
### 24. VMPL Shoping
~~~
https://ali-abdullah.ml/APIS/vmpl?number=01xxxxxxxxx
~~~
### 25. Web Access
~~~
https://ali-abdullah.ml/APIS/swap?number=01xxxxxxxxx
~~~

# Uses

- CHANGE THE `(API NAME)`
- TO USE MULTIPLE APIS USE SAME CODE 1 by 1

## PHP
~~~php
<?php
$url = "https://ali-abdullah.ml/APIS/(API NAME)?number=01xxxxxxxxx";
$curl = curl_init($url);
curl_setopt($curl, CURLOPT_URL, $url);
curl_setopt($curl, CURLOPT_RETURNTRANSFER, true);
curl_setopt($curl, CURLOPT_SSL_VERIFYHOST, false);
curl_setopt($curl, CURLOPT_SSL_VERIFYPEER, false);
$resp = curl_exec($curl);
curl_close($curl);
var_dump($resp);
?>
~~~
## JAVASCRIPT
~~~javascript
var url = "https://ali-abdullah.ml/APIS/(API NAME)?number=01xxxxxxxxx";
var xhr = new XMLHttpRequest();
xhr.open("GET", url);
xhr.onreadystatechange = function () {
   if (xhr.readyState === 4) {
      console.log(xhr.status);
      console.log(xhr.responseText);
   }};
xhr.send();
~~~
## BASH
~~~bash
#!/bin/bash
curl -X GET https://ali-abdullah.ml/APIS/(API NAME)?number=01xxxxxxxxx 
~~~
## PYTHON
~~~python
import requests
url = "https://ali-abdullah.ml/APIS/(API NAME)?number=01xxxxxxxxx"
resp = requests.get(url)
print(resp.status_code)
~~~
