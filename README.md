# Space Tracker App

1. Galaxies
Get All Galaxies

curl -X GET http://localhost:3000/galaxies
GET Galaxies by ID

curl -X GET http://localhost:3000/galaxies/1
Create New Galaxy

curl -X POST http://localhost:3000/galaxies \
-H "Content-Type: application/json" \
-d '{"name": "Milky Way", "size": 1000, "description": "Our galaxy"}'
Update Galaxy By ID

curl -X PUT http://localhost:3000/galaxies/ \
-H "Content-Type: application/json" \
-d '{"name": "Andromeda", "size": 2200, "description": "The nearest galaxy to us."}'
Delete Galaxy By ID

curl -X DELETE http://localhost:3000/galaxies/1
2. Planets
Get All Planets

curl -X GET http://localhost:3000/planets
GET Planets by ID

curl -X GET http://localhost:3000/planets/1
Create New Planet

curl -X POST http://localhost:3000/planets \
-H "Content-Type: application/json" \
-d '{"name": "Earth", "size": 122, "description": "The third planet from the Sun."}'
Update Planet By ID

curl -X PUT http://localhost:3000/planets/1 \
-H "Content-Type: application/json" \
-d '{"name": "Mars", "size": 679, "description": "The fourth planet from the Sun."}'
Delete Planet By ID

curl -X DELETE http://localhost:3000/planets/1
3. Stars
Get All Stars

curl -X GET http://localhost:3000/stars
GET Stars by ID

curl -X GET http://localhost:3000/stars/1
Create New Star

curl -X POST http://localhost:3000/stars \
-H "Content-Type: application/json" \
-d '{"name": "Sun", "size": 1300, "description": "The star at the center of our solar system."}'
Update Star By ID

curl -X PUT http://localhost:3000/stars/1 \
-H "Content-Type: application/json" \
-d '{"name": "Sirius", "size": 1155, "description": "The brightest star in the night sky."}'
Delete Star By ID

curl -X DELETE http://localhost:3000/stars/1