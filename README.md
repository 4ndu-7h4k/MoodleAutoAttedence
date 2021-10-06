<h1 align= center>Moodle Auto-Attendence </h1>
<h3 align = center>Python script to mark moodle course attedence</h3>

<<<<<<< HEAD
### Heroku
<p><a href="https://heroku.com/deploy?template=https://github.com/4ndu-7h4k/MoodleAttendence"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>


## Deploy Locally or Server
```
$ git clone https://github.com/4ndu-7h4k/MoodleAttendence
$ cd MoodleAttendence
$ pip3 install -U -r requirements.txt
$ nano moodle/config.py
=======
### Heroku
<p><a href="https://heroku.com/deploy?template=https://github.com/4ndu-7h4k/MoodleAutoAttendence"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>


## Deploy Locally or Server
```
git clone https://github.com/4ndu-7h4k/MoodleAttendence
cd MoodleAttendence
pip3 install -U -r requirements.txt
nano moodle/config.py
>>>>>>> 23448168e2d7d256784b857e8e8a4b6f51feb1c9
#Fill config with your values , set server = False if not using .env
cp sample.env .env
#Fill .env with values
python3 -m moodle
 ```
## Note
 This is a Dev branch, So you might experience bugs!
