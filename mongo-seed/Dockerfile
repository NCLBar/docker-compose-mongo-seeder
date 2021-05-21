FROM mongo

COPY init.json /init.json
CMD mongoimport --host mongodb --db TestDB --collection TestCollection --type json --file /init.json --jsonArray