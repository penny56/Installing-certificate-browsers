Installing in Firefox v57+ versions

1- Within your Firefox browser application (v57+ version), click on the following links:

https://daymvs1.pok.ibm.com:2443/PKIServ/cacerts/carootcert.der                    -->  IBM CA/PKI Root certificate

https://daymvs1.pok.ibm.com:2443/PKIServ/cacerts/caintermediatecert.der      -->  IBM CA/PKI Intermediate certificate

 

2- Pop-up messages will be displayed for each URL, in both cases select "Trust this CA to identify websites." option, then click "OK" :



 * Pop-up message for IBM CA/PKI Root certificate

 



 * Pop-up message for IBM CA/PKI Intermediate certificate

3- If you want to review the certificate import process was successful, paste in the URL address bar:     about:preferences




4- In the left menu, select "Privacy & Security":



 

5- Scroll down until the bottom of the page and select "View Certificates":



 

6- Go to the "Authorities" tab, and search for "International Business Machine Corporation", then you'll have to see both certificates (Root and Intermediate) installed:

