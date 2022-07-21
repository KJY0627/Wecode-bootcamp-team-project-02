# Greeneeds
![GREENEEDS(edit)](https://user-images.githubusercontent.com/100059297/180118666-481bc051-5a07-4f29-9cea-28be04d1c47d.gif)




## Introduction
This is a repository for a clone coding project. 'Crowdfunding website-[Tumblbug]'(https://tumblbug.com/discover) 

- Project period: 07.04.22 ~ 07.15.22
- Team 'Greeneeds': Front-End 4 / Back-End 2
- [Front-end Github](https://github.com/wecode-bootcamp-korea/34-2nd-greeneeds-frontend)
- Collaboration tools: Github, Trello, Slack, Notion

</br>

## Project Objective
- Built a server via Django framework
- Implemented MySQL DataBase
- Signup function via Kakao API(South Korea's social network service)
- Projects uploading function from Django to S3

</br>

## DB Modeling
![greeneeds Databases](https://user-images.githubusercontent.com/65996045/178923387-db892fc9-ed98-4c26-ab4f-57360aa0f305.png)

</br>

## Technologies
- Python
- Django Web Framewrok
- MySQL
- Git, Github
- AWS(EC2, RDS, S3)

</br>

## Features
**User**
1. Signup (POST)
    - Connected with Kakao social API
    - Kakao login Unit test
2. Login (POST)
    - Implemented JWT Access Token

</br>

**Project**
1. Projects list page (GET)
	-Using Query Parameter
Sorting as 2 types that order by 'like', 'recent' 
2. Projects detail page (GET)
	- Using Path Parameter
3. Upload projects (POST)
	- Uploaded images via S3
	- returned images uploaded as url-type

</br>

**Like**
1. Likes function (POST)
	- Add likes and delete

</br>

## API Documentation
- [API Documentation](https://velog.io/@chaduri7913/Greeneeds-API-Documentation)
