# hello-world
Test Repository


pal_user@germs:~/workspace/pal-tracker$ cf create-route sandbox apps.pikes.pal.pivotal.io --hostname pal-tracker-22
Creating route pal-tracker-22.apps.pikes.pal.pivotal.io for org swagat-pattnaik / space sandbox as spattnai@ford.com...
Route pal-tracker-22.apps.pikes.pal.pivotal.io has been created.
OK

--------------
pal_user@germs:~/workspace/pal-tracker$ cf map-route pal-tracker apps.pikes.pal.pivotal.io --hostname pal-tracker-22
Creating route pal-tracker-22.apps.pikes.pal.pivotal.io for org swagat-pattnaik / space sandbox as spattnai@ford.com...
OK
Route pal-tracker-22.apps.pikes.pal.pivotal.io already exists
Adding route pal-tracker-22.apps.pikes.pal.pivotal.io to app pal-tracker in org swagat-pattnaik / space sandbox as spattnai@ford.com...
OK
pal_user@germs:~/workspace/pal-tracker$ cf apps
Getting apps in org swagat-pattnaik / space sandbox as spattnai@ford.com...
OK

name          requested state   instances   memory   disk   urls
map-route     started           1/1         1G       1G     map-route-fearless-okapi.apps.pikes.pal.pivotal.io
pal-tracker   started           1/1         1G       1G     pal-tracker-silly-raven.apps.pikes.pal.pivotal.io, pal-tracker-22.apps.pikes.pal.pivotal.io
pal_user@germs:~/workspace/pal-tracker$ 
