### NO-SQL CHALLENGE
#### nOsql_SETUP_Starter
- json file in Resources : establishment has been stored in a Mongo DB database uk_food and assigned to variable db for further analysis in Pymonngo .
- Update of Data base has been conducted and Datatype has been modified for future evaluations:
-test = establishments.find_one({})

pprint(type(test['RatingValue']))
pprint(type(test['geocode']['longitude']))
pprint(type(test['geocode']['latitude']))   
<class 'int'>
<class 'bson.decimal128.Decimal128'>
<class 'bson.decimal128.Decimal128'>
#### NoSQL_analysis_starter
Packages: pymongo(MongoClient), pprint (pprint),pandas (DataFrame), pandas (pd)

##### Exploratory Analysis
1) total establishments with Hygene score 20 is: 41
class 'pandas.core.frame.DataFrame'>
RangeIndex: 41 entries, 0 to 40
Data columns (total 30 columns):
![image](https://github.com/pmadata/nosql-challenge/assets/143486132/5abc43e7-f727-4a43-8156-2fc2e6633da8)
2)Total of establishments with London as the Local Authority: 33
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 33 entries, 0 to 32
Data columns (total 30 columns):
![image](https://github.com/pmadata/nosql-challenge/assets/143486132/745d42c0-5302-4b3d-8841-97948985d403)
3) What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
   ![image](https://github.com/pmadata/nosql-challenge/assets/143486132/d974269b-5a4e-4d26-b6c7-8aedfe6f3cb9)
4) How many establishments in each Local Authority area have a hygiene score of 0?
   ![image](https://github.com/pmadata/nosql-challenge/assets/143486132/9a1c8c9d-a32f-4dcc-a15b-36dbc5c28bd3)

References: for this assigments parts of code have been used based on previous activities in class and also support from Anaconda Assistant 0.5.12
