Setting up windows desktop for DevOps and Cloud
-------------------------------------------------
### Required softwares are
* Chocolatey
* Git
* Visual Studio Code

* For the above softwares to be install, we need One New Windows Desktop.
* For that we will create Windows instance in AWS cloud.
* To start with login aws console and search for EC2 resource in Compute.
* All the required fields are filled with your requirement and Launch the Instance.
* Go to aws console and select launch instances in instances.
![Preview](Images/soft1.png)

* To select name of the instance is `test`, Application and OS Images (AMI) is `windows`, and instance type is `t2.small`.
![Preview](Images/soft2.png)

* After that create new key pair with name `test`, make Network settings and Configure storage as default.
![Preview](Images/soft3.png)
![Preview](Images/soft4.png)
![Preview](Images/soft5.png)
![Preview](Images/soft6.png)

* Wait for status check to be passed `2/2 checks passed`.
![Preview](Images/soft7.png)

* Press the connect and it will take to you for RDP client
![Preview](Images/soft8.png)

* Tap on RDP client and little bit scroll down you will see a `Get password` you can tap on it.
* it will asks you a private file and browse for `.pem` file in our local and finally press on Decrypt password, it will give a password to connect a New Desktop.
![Preview](Images/soft9.png)
![Preview](Images/soft10.png)
![Preview](Images/soft11.png)
![Preview](Images/soft12.png)
![Preview](Images/soft13.png)

* Open Remote Desktop Connection computer as `Public DNS` copy and paste it over `computer`.
![Preview](Images/soft14.png)
![Preview](Images/soft15.png)
![Preview](Images/soft16.png)
![Preview](Images/soft17.png)
![Preview](Images/soft18.png)
![Preview](Images/soft19.png)
![Preview](Images/soft20.png)
![Preview](Images/soft21.png)

* Close the windows powershell and reopen as an administrator and check for `choco --version` choco is the short form of chocolatey.
![Preview](Images/soft22.png)

* Now install git, for that open browser and search for choco install git, copy the command and paste it over windows powershell run as an administrator.
![Preview](Images/soft23.png)

* Git install using choco.
![Preview](Images/soft24.png)

* Go to aws cloud and login into console
* Launch an instance with name is practice and ami is ununtu and instance type is t2.micro and network settings leave it as default and Click on launch instance.
![Preview](Images/soft26.png)
![Preview](Images/soft27.png)


* Open Git Bash and connect to the server using ssh
![Preview](Images/soft25.png)
![Preview](Images/soft28.png)
![Preview](Images/soft29.png)

* Finally we got the result
![Preview](Images/soft30.png)

Note:
-----
* Don't forget to terminate the instances what you have created.
![Preview](Images/soft31.png)
![Preview](Images/soft32.png)
![Preview](Images/soft33.png)

THANKS FO READING!
