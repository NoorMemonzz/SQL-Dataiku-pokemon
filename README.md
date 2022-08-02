# SQL-Dataiku-pokemon
The  SQL code for every file is shared in README file 
NOTE: Code is same for the tasks but make sure to make changes in saved file names. 


SQL_basic_query_file1
-----------------------------------------------------------------------------------------------------------------------------------------------------------
Dataiku code for file1 basics

SELECT a."Name", a."HP", a."Attack", a."Defense", a."Legendary", b."Survived"
FROM "public"."NOOR_MEMONZZ_BOSTON_pokemon_noor_memonzz_sql_num" a
LEFT JOIN "NOOR_MEMONZZ_BOSTON_pokemon_battles_noor_memonzz_sql" b
ON a."Name" = b."Name_1"
WHERE a."HP" > 100 AND a."Legendary" = true
![image](https://user-images.githubusercontent.com/106626918/182283015-d326a253-5215-471e-aa33-52d7b1c51d5d.png)

-----------------------------------------------------------------------------------------------------------------------------------------------------------

