<p align="center">
<a href="https://dscvit.com">
	<img src="https://user-images.githubusercontent.com/30529572/72455010-fb38d400-37e7-11ea-9c1e-8cdeb5f5906e.png" />
</a>
	<h2 align="center"> DSC Challenges App </h2>
	<h4 align="center"> An App for conducting DSC Challenges - daily and weekly challenges. <h4>
</p>

---
[![DOCS](https://img.shields.io/badge/Documentation-see%20docs-green?style=flat-square&logo=appveyor)](INSERT_LINK_FOR_DOCS_HERE) 
  [![UI ](https://img.shields.io/badge/User%20Interface-Link%20to%20UI-orange?style=flat-square&logo=appveyor)](INSERT_UI_LINK_HERE)


## Functionalities
- [ ]  Login using Oauth
- [ ]  Bulk adding of questions to the DB
- [ ]  Questions will be picked randomly from a question bank
- [ ]  Answering questions
- [ ]  Maintain Score Leaderbord
- [ ]  Seperate Leaderboard and question bank for specific domains

<br>


## Instructions to run

* Pre-requisites:
	-  Python

* Directions to install
	- Clone the Repositiory
	```bash
	git clone https://github.com/GDGVIT/dsc-challenge-backend.git
	```
	- Setting up a virtual env 
	```bash
	virtualenv env
	env\Scripts\activate
	```
	- Installing Packages
	```bash
	pip install -r requirements.txt
	```
	- Making migrations
	```bash
	python manage.py migrate
	````

* Run the server

	```bash
	python manage.py runserver 3000
	```


## Contributors

<table>
<tr align="center">


<td>

Riddhi Gupta

<p align="center">
<img src = "https://avatars2.githubusercontent.com/u/43917576?s=460&u=b9ba679a93963e9dd0cc8b849dce4cfc26c4f24f&v=4" width="150" height="150" alt="Riddhi Gupta">
</p>
<p align="center">
<a href = "https://github.com/RiddhiGupta5"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/riddhi-gupta-6a587017a">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>


<td>

Siddhartha Varma 

<p align="center">
<img src = "https://avatars1.githubusercontent.com/u/39856034?s=400&u=b2f0ffe4ff639d4257db47e7268ed22e8aaf0221&v=4" width="150" height="150" alt="Your Name Here (Insert Your Image Link In Src">
</p>
<p align="center">
<a href = "https://github.com/BRO3886"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/siddharthav22/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/>
</a>
</p>
</td>

</tr>
  </table>

<br>
<br>

<p align="center">
	Made with :heart: by <a href="https://dscvit.com">DSC VIT</a>
</p>

