FROM mongo

COPY users.json .

CMD mongoimport --host mongo --db mean --collection users --type json --file /users.json --jsonArray
