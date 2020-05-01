# IIEC_Docker_Course_Project

 **Mr Vimal Daga** a WORLD RECORD HOLDER initiated with a 
community named as **IIEC** under which he started giving online 
training of some courses for students like us and the course
was totally free of cost. 
Of one of them courses was Docker of which he took 7 sessions
And one session was introductory. After successfully 
completing the course I implemented the knowledge of that
training by creating this project. 
 
## 1.Description about the Project:
 My project is basically upon deployment of a website/webapp
in one click. It consists of a website on which anybody can
blog and everybody connected to the same server can see the 
the blog of that person
* Used javascript for the blog
* Used for MySQL for database management
* Used nextcloud for web applications

## 2.Pre-requisites for the system:
* RHEL 8 should be installed in your system
* Any OS can be used
* Must have **Docker** software installed in your system
* Should be known to some basic linux commands for ease of operation
* Use `systemctl stop firewalld`
* Use `systemctl start Docker` for starting Docker services in your system

## 3.For the images in the project:
* Pulling MySQL Image:
  * For downloading the **mysql version 5.6** image, apply this code `docker pull mysql:5.6` for using this as a database server.
* Pulling nextcloud Image:
  *For downloading the **nextcloud** Image, apply this code `docker pull nextcloud:18.0.4-apache`  in which apache server is
 already preconfigured.

## 4. For MySQL:
* Use `yum install mysql` for installing **My SQL Client Software**
and through their you can have a check on your MySQL database

## 5. Docker_Compose:
* Before using Docker-Compose you should install the software. For reference go to this website : https://docs.docker.com/compose/install/

* You can create and edit this file using vim editor. For that use `vim docker-compose.yml`. Remember the file name should always be **docker-compose.yml**

## version: Every version has a different form of syntax
## services: 























