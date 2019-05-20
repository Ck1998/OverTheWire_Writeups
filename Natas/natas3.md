# natas3

**URL:** [http://natas3.natas.labs.overthewire.org](http://natas3.natas.labs.overthewire.org)<br>
**Username:** natas3<br>
**Password:** sJIJNW6ucpu6HPZ1ZAchaDtwd7oGrD14<br>
 
Challenge:
To find the password for the next level i.e natas4.

Upon opening the url and entering the credentials, the following page shows up- 
![alt text](https://i.imgur.com/rwuL6qY.png?1)

Upon viewing the source code for the page:
![alt text](https://i.imgur.com/8Z44feY.png?1)

Now we see that there is a comment 'No more information leaks!! Not even Google will find it this time...' this might mean that there is a directory which google's spider might not crawl, means we have to look at the ' robots.txt ' file. on visiting the url [http://natas2.natas.labs.overthewire.org/robots.txt](http://natas2.natas.labs.overthewire.org/robots.txt) , we get the following page:
![alt text](https://i.imgur.com/SiwW2BC.png?1)

Now we know that there is a directory named ' /s3cr3t/ '. on following the url [http://natas2.natas.labs.overthewire.org/s3cr3t/](http://natas2.natas.labs.overthewire.org//s3cr3t/), we get: 
![alt text](https://i.imgur.com/OdG3i8t.png?1)

Checking the "users.txt" file, we have:
![alt text](https://i.imgur.com/7sGs2zj.png?1)

we have the password for natas4

#### Password for natas4: **Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ**
