 [![bagde](https://codeship.com/projects/e4a1d8b0-8b71-0134-1c87-26c6b97868f1/status?branch=master)](https://codeship.com/projects/184622)
# spring-boot-scaffold-kotlin

#About
Generate api scaffold kotlin with spring boot rest, creating a api rest with kotlin and spring boot in an easy and productive way.

Scaffold for java web, a clean generate with simple classes.



#Architecture

           __br
              __com
                  __scaffold
                           MainApplication.java
                           __domain
                                 Model.kt
                           __repository
                                 Repository.kt
                           __service
                                 Service.kt
                           __controller
                                 Controller.kt
        
#Alert
In development. Help us! Make a fork!

#Requeriments
         
* java

#Install 

###Using npm (windows) linux(todo)
     npm install spring-boot-api-scaffold@0.0.1

###or add the environment variable

###windows
   * [cli.bat](https://raw.githubusercontent.com/NetoDevel/spring-boot-scaffold-kotlin/master/spring-boot-generate/src/main/resources/install/windows/cli.bat)
   * [spring-api-kotlin-0.1.jar](https://raw.githubusercontent.com/NetoDevel/spring-boot-scaffold-kotlin/master/spring-boot-generate/src/main/resources/install/windows/spring-api-kotlin-0.1.jar)

###Linux
   * todo


#Usage

###Create project

         cli -spring g new my-project

###Generate model
   
        cli -spring g model User mail:String password:String

###Generate repository

        cli -spring g repository User 

###Generate service
        
        cli -spring g service User
        
###Generate controller

        cli -spring g controller User
        
###Generate scaffold

        cli -spring g scaffold User mail:String password:String

###Todo

* validates types variables
* validates exists project,class
* set package to generate
* install linux/windows single package node
* gradle support
* generate Test JUnit @SpringBootTest
* sample using scaffold
* remove prefix cli

###Acknowledgment
         
 * [Bruno Lima](https://github.com/brunodles)
 * [Ivan Marreta](https://github.com/ivanmarreta)
       

