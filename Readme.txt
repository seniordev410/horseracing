Web crawling (data crawling) from a horse racing website.
Website name: racingpost.com 
Work includes: 
   - Scrapping per day automatically, or Manually. 
   - Developing Query tools with full options. 
   - Exporting data from the database to CSV.

https://genesis-data.herokuapp.com/

1. cd horseracing
2. pip install -r requirement.txt
3. python manage.py makemigrations
4. python manage.py migrate
5. load default data
    python load_data.py # insert all data from csv file to database
6. python manage.py runserver

worker: python manage.py qcluster
