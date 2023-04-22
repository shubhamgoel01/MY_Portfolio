# MY_Portfolio : https://shubham1921.pythonanywhere.com/
```bash

---------- Steps To Run Production code into Local --------------
git clone https://github.com/shubhamgoel01/MY_Portfolio.git    (work on main branch : production code)
pip install -r req.txt
python manage.py makemigrates
python manage.py migrate
vim MY_Portfolio/personal_portfolio/settings.py

* Find below detials :
DEBUG = False
ALLOWED_HOSTS = ['Shubham1921.pythonanywhere.com']

Make changes as like below :

DEBUG = True
ALLOWED_HOSTS = ['Shubham1921.pythonanywhere.com','*']

Finally run :
python manage.py runserver 
```

------------ STEPS to change Image on Production---------------
```bash
To activate/deactivate environment on pythonanywhere
12:42 ~/MY_Portfolio (main)$  workon portfolioenv 
12:42 ~/MY_Portfolio (main)$  deacivate

After clone or Pull  here : 
12:42 ~/MY_Portfolio (main)$  cd MY_Portfolio/
(portfolioenv) 12:42 ~/MY_Portfolio (main)$ dir
README.md  blog  db.sqlite3  manage.py  media  personal_portfolio  portfolio  req.txt  requirements.txt  screenshot  static

(portfolioenv) 15:45 ~/MY_Portfolio (main)$ ls static/portfolio/                                                                                                       
Logo.png  custom.css  resume.pdf  shubham.jpg

change this image `shubham.jpg` or delete/upload on pythonanywhere directly and commit after that changes

------------ STEPS to change Image on Local (different path)---------------

$ ll MY_Portfolio/portfolio/static/portfolio/
total 785
-rw-r--r-- 1 shubh 197609    380 Apr 22 20:44 custom.css
-rw-r--r-- 1 shubh 197609 442438 Apr 22 20:44 Logo.png
-rw-r--r-- 1 shubh 197609 193581 Apr 22 20:44 resume.pdf
-rw-r--r-- 1 shubh 197609  96873 Apr 22 20:44 shubham.jpg
-rw-r--r-- 1 shubh 197609  58493 Apr 22 20:44 shubham-bkp.jpg

change this image `shubham.jpg`
```

![alt text](https://github.com/shubhamgoel01/MY_Portfolio/blob/main/screenshot/portfolio1.png?raw=true) 

#2
![alt text](https://github.com/shubhamgoel01/MY_Portfolio/blob/main/screenshot/portfolio2.png?raw=true)

#Blogs
![alt text](https://github.com/shubhamgoel01/MY_Portfolio/blob/main/screenshot/portfolio3.png?raw=true)
