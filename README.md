# dspwebsite

The code for www.dspduke.com. Made with jaypatel37 using Django, Bootstrap, HTML, CSS, and Javascript


To download requirements and run locally, 

```
pip3 install -r requirements.txt
python3 manage.py runserver 
``` 


Key files:
mainwebsite/templates/main/index.html

mainwebsite/static/main/css/grayscale.css

mainwebsite/static/main/js/grayscale.js


To log changes on github use:
```
git add .

git commit -m 'your message here'

git push
```

The main landing page for the website is found in mainwebsite/templates/main/index.html. The exec team and recruitment page should be updated yearly.

Images are stored in mainwebsite/static/img

To push changes to the hosting server, use 

```
git push heroku master
```

