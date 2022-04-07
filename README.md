# PostmanAPIWithCSV1
newman run WH_Mercury_Lection4.postman_collection.json -d WH_Mercury_Lection4.csv -r htmlextra


# or for jenkins job:

newman run WH_Mercury_Lection4.postman_collection.json --iteration-data WH_Mercury_Lection4.csv --disable-unicode --reporters cli,htmlextra
