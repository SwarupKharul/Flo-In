<p align="center">
    <a href="https://stcvit.in/" target="_blank"><img src="https://github.com/STCVIT/STC-README/blob/master/gitbanner.png" title="STC-VIT" alt="STC-VIT"></a>
</p>

<center>

# FLO-IN
> FLO-IN is the smartest way to log in using facial recognition.
</center>

---
<p>
  <a href="https://stcvit.in/" target="_blank">
    <img alt="made-by-stc" src="https://img.shields.io/badge/MADE%20BY-STC%20VIT-blue?style=for-the-badge" />
  </a>

  <a href='https://github.com/STCVIT/Flo-In/blob/master/LICENSE' target="_blank">
  <img alt="license" src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" />
  </a>
    
</p>


<a href="https://floin-project.azurewebsites.net/">FLO-IN</a> is an extension that recognises a user whenever he/she tries to Log-In any of the accounts. The user who has registered his/her face will only be given the option to access the accounts. The face recognition will be done every time the user tries to access any of the accounts. Option to open the accounts via pattern is also provided. Hence, there is no need to Log-Out every time of the account to keep the data safe. Without any single click you can access your accounts as well as keep the account password protected.

<br>


## Built With
| | | | |
|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|
|<a href="https://www.djangoproject.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-original.svg" alt="django" width="100" height="100"/> </a>|<a href="https://opencv.org/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-ar21.svg" alt="opencv" width="150" height="70"/> </a>| <a href="https://opencv.org/" target="_blank"> <img src="assets/mediapipe.png" alt="Mediapipe" width="210" height="50"/> </a>| <a href="" target="_blank"><img src="https://www.vectorlogo.zone/logos/getbootstrap/getbootstrap-ar21.svg" alt="bootstrap" width="200" height="100" /></a>




## 💪🏻 Features
- Save Password
- Auto-Fill with Facial Recognition 
- PIN Login 



## 👨‍💻 Dependencies
 - Chrome Browser
 - Python 3.8
 - Dlib



## 🏃‍♀️ Getting Started
### Running locally

- Clone the repository
```
git clone https://github.com/STCVIT/Flo-In.git 
```
- Install the dependencies
```
pip install -r requirements.txt
```
- Start the server
```
python manage.py runserver
```

### Running this app using Docker

You'll need to have [Docker installed](https://docs.docker.com/get-docker/).
It's available on Windows, macOS and most distros of Linux. If you're new to
Docker and want to learn it in detail check out the [additional resources
links](#learn-more-about-docker-and-django) near the bottom of this README.

If you're using Windows, it will be expected that you're following along inside
of [WSL or WSL
2](https://nickjanetakis.com/blog/a-linux-dev-environment-on-windows-with-wsl-2-docker-desktop-and-more).
That's because we're going to be running shell commands. You can always modify
these commands for PowerShell if you want.

#### Clone this repo anywhere you want and move into the directory:

```sh
git clone https://github.com/STCVIT/Flo-In.git
cd FloIn

# Optionally checkout a specific tag, such as: git checkout 0.4.0
```

#### Build everything:

*The first time you run this it's going to take 5-10 minutes depending on your
internet connection speed and computer's hardware specs. That's because it's
going to download a few Docker images and build the Python*

```sh
docker build --tag floin:latest .
```

Now that everything is built. To get the app running use this command.


```sh
docker run --name floin -d -p 8000:8000 floin:latest
```

#### Setup the initial database:

```sh
./run manage migrate 
```

*We'll go over that `./run` script in a bit!*

#### Check it out in a browser:

Visit <http://localhost:8000> in your favorite browser.



## 🙌 Contributions

- Feel Free to Open a PR/Issue for any feature or bug(s).
- Make sure you follow the [community guidelines](https://docs.github.com/en/github/site-policy/github-community-guidelines)!
- Have a feature request? Open an Issue!



## ⭐ Show your support

Give a ⭐ if this tool made your life easier!

Spread the word to your geek fellows to save their time!



## ✨ Contributors

## Contributors
<table>
	<tr align="center" style="font-weight:bold">
		<td>
		Swarup Kharul
		<p align="center">
			<img src = "https://avatars.githubusercontent.com/u/65753949?v=4" width="150" height="150" alt="Swarup Kharul">
		</p>
			<p align="center">
				<a href = "https://github.com/SwarupKharul">
					<img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
				</a>
			</p>
		</td>
		<td>
		Vanshika Nehra
		<p align="center">
			<img src = "https://avatars.githubusercontent.com/u/72328934?v=4" width="150" height="150" alt="Vanshika Nehra">
		</p>
			<p align="center">
				<a href = "https://github.com/VanshikaNehra23">
					<img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
				</a>
			</p>
		</td>
		<td>
		Vineet Raj
		<p align="center">
			<img src = "https://avatars.githubusercontent.com/u/74700202?v=4" width="150" height="150" alt="Vineet Raj">
		</p>
			<p align="center">
				<a href = "https://github.com/vinmik">
					<img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
				</a>
			</p>
		</td>
		<td>
		Suryakant Agrawal
		<p align="center">
			<img src = "https://avatars.githubusercontent.com/u/72617587?v=4" width="150" height="150" alt="Swarup Kharul">
		</p>
			<p align="center">
				<a href = "https://github.com/suryaa62">
					<img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
				</a>
			</p>
		</td>
		<td>
	</tr>
	</table>


* [Harshita Rajput](https://github.com/HarshitaRajput)


## 🤝🏻 Connect with Us
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/mstcvit/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/micvitvellore/mycompany/)

[![Join Us](https://img.shields.io/badge/Join%20Us-STC-VIT)](https://stcvit.in/)

<p align="center">
	Made with :heart: by <a href="https://stcvit.in/">STC-VIT</a>
</p>
