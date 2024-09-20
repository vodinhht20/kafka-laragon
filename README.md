# How to install the rd-kafka extension for Laragon
### Steps

Step 1: Go to the link https://pecl.php.net/package/rdkafka to download the rdkafka version compatible with your PHP version and extract the files.
Note: Download the Thread Safe (TS) x64 DLL version.
![image](https://github.com/user-attachments/assets/8ded5001-cf65-4766-ade8-083fb727404d)

Step 2: Navigate to the PHP extension folder in Laragon. Then, copy the two extracted files to the following locations:
![image](https://github.com/user-attachments/assets/ab7468c7-7923-4955-b346-18a673c22c15)

librdkafka.dll -> laragon\bin\php\php-my-version
php_rdkafka.dll -> laragon\bin\php\php-my-version\ext

![image](https://github.com/user-attachments/assets/1970cb72-6c88-418e-86bf-93fe8f69b59f)
![image](https://github.com/user-attachments/assets/73595255-18c8-4abc-80af-45a7f7a7021b)

Step 3: Restart Laragon.
![image](https://github.com/user-attachments/assets/19f4f068-27e6-4570-b4fa-c98a506052d4)

Step 4: Enjoy!
![image](https://github.com/user-attachments/assets/69f6b89b-06cf-46a8-94c0-6b70492490ac)

