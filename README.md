# Project 8 - Pentesting Live Targets

Time spent: **9** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: Blue Session Hijacking: Use to login to by pass to user another browser to get fiddent ID and user information can get steal information.

GIF Walkthrough:
![Blue1-ID](https://user-images.githubusercontent.com/36207058/56153173-877d4880-5f83-11e9-88c3-a9f8ed993b97.gif)

Vulnerability #2: Blue SQL injection: On the sit of the blue is input not going to be sanitized beofe uses in an SAQL quesry in blue SQL injection.

GIF Walkthrough:
![Blue1-SQL](https://user-images.githubusercontent.com/36207058/56153198-9663fb00-5f83-11e9-8dd2-781455dcfc09.gif)

## Green

Vulnerability #1: Cross Site Scripting(XSS)

GIF Walkthrough:
![GreenXSS](https://user-images.githubusercontent.com/36207058/56153241-abd92500-5f83-11e9-8809-661e4c78c549.gif)

Vulnerability #2: Green_User_Enumeration: In web-application can perfroam to give hints for user exits or not in green User_Enumeration.

GIF Walkthrough:
![Green_Username_Enumeration1](https://user-images.githubusercontent.com/36207058/56153221-9fed6300-5f83-11e9-8523-5b0412cc0a23.gif)


## Red

Vulnerability #1: Insecure Direct Object Reference(IDOR): using the code for red missing of color and information made by using the public.

GIF Walkthrough:
![Red_i](https://user-images.githubusercontent.com/36207058/56153280-c4e1d600-5f83-11e9-9999-da15b17309d4.gif)


Vulnerability #2: Cross-Site Request Forgery(CSRF): CSRF red site doesnt have perimsion using the admin area.

GIF Walkthrough:
![RedCSRF](https://user-images.githubusercontent.com/36207058/56153256-ba274100-5f83-11e9-85b6-71550e59a74a.gif)

## Notes

Describe any challenges encountered while doing the work

