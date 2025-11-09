# java_server_demo
The aim is to understand how networking works....we will make our own pc a global server


## steps
1. To make http to https we need ssl certifice file "keystore.jks" in the working directory
   Run this Command
    ```
    keytool -genkeypair -alias myserver -keyalg RSA -keysize 2048 -validity 365 -keystore keystore.jks -storepass password
    ```

2. To make ```https://192.168.1.4:8000/``` to local name like ```https://om:8000/``` add the below line  in ```C:\Windows\System32\drivers\etc\hosts``` as administrator
  ```
  192.168.1.4  om
  ```

