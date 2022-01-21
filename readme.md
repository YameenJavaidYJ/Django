firstofall activate the virtual environemnt
-> virtualenv dj_ds
-> cd dj_ds
-> source bin/activate
-> pip install django

We will be creating a reports project that will further contain django-apps inside

start project
-> djangoadmin start project reports_proj

move reports_proj into a src folder as per django directory standards
-> mv reports_proj src

manage.py will be used for most of the tasks associated with our django application

next we create tables in our database
-> python manage.py migrate

we will be creating a super user to login for our projects administration side
-> python manage.py create superuser
-> username: yameen
-> password: xyz123

we will make our sales app using (manage.py startapp)
-> python manage.py startapp sales

we will make our reports app using (manage.py startapp)
-> python manage.py startapp reports

we will make our customers app using (manage.py startapp)
-> python manage.py startapp customers

we will make our profiles app using (manage.py startapp)
-> python manage.py startapp profiles

we will make our products app using (manage.py startapp)
-> python manage.py startapp products

we will run the server
-> python manage.py run
-> copy the address (127.0.0.1:8000) open in the browser

once on the browser for the first time login to administrator side

