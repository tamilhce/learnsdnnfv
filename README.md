# learnsdnnfv
website 
i) while port to new vm machine   
step 1 : mkdir mysite 
step 2 : chmod -R 777 mysite
step 3 : djangocms -f -p . mysite
         'don't worry if its throw error in data base creation 
step 4 : In settings.py  change 
         i) database name ===> adsolutepath + name 
         ii) Allowed host ===> your domain name 
step5 : 
python manage.py migrate

step 6 : python manage.py  syncdb
