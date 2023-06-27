Description: Camaleon CMS v2.7.4 was discovered to contain a Cross Site Scripting (store XSS).

Affected Component: All versions that are below 2.7.4

Step to reproduce: Detection and Exploitation: 
1. Go to seting content group 

2.Inject payload : "' test <img src="" onerror="alert(3)"> to name of post type

3. Access to admin page. Then the script is execute

POC:

![image](https://github.com/anh91/Camaleon-xss/assets/132877337/d0d29f62-efcc-4af7-8bb3-206aac31ec08)

![image](https://github.com/anh91/Camaleon-xss/assets/132877337/4c9e6a45-993a-4056-8509-50cb210a6f78)

![image](https://github.com/anh91/Camaleon-xss/assets/132877337/a1f6696a-dbe4-422f-9a48-6aa15cc991d4)

