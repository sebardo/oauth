rest
====

Call to retrieve access_token (client must have grant_type="client_credentials"):

curl 'http://127.0.0.1:8000/oauth/v2/token?
grant_type=client_credentials&
client_id=6_2p9r8qlmngmc44sc48o8g0gko4c404swsgwo0osgk4gk8o8sgs&
client_secret=2vz7pzy1jack0wc4c40sk8kwkosc4wo4ks080wwwsco4sw4w8c&
scope=read'

ODYwMjgwNjhkM2EzYjI2MGMyMDgzYTA4Mzc5ZDYyZTAwZWVlNTdhNzlhZmFjYWJkMTkyYTY5YjE3MDZmOGI1Nw


curl 'http://127.0.0.1:8000/api/user/2' -H 'Authorization: Bearer ODYwMjgwNjhkM2EzYjI2MGMyMDgzYTA4Mzc5ZDYyZTAwZWVlNTdhNzlhZmFjYWJkMTkyYTY5YjE3MDZmOGI1Nw'
