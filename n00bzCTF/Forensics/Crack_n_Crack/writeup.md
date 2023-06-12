# **Crack & Crack**
## **Task**
Just Crack & Crack! 

* [Task](https://ctf.n00bzunit3d.xyz/challenges#Crack%20&%20Crack-8)

* Author: NoobMaster

* 500 **pts**

## **File**
![File](flag.zip)

## **Steps**

the pdf file zipped with password 

![](capture1.png)

we will use a dictionary attack to crack a ZIP password with **fcrackzip**

	fcrackzip -u -D -p rockyou.txt flag.zip

The password of flag.zip

![](zip_password.png)

* 1337h4x0r
