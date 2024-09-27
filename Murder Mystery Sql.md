SELECT * 
FROM crime_scene_report
LIMIT 5;
![image](https://github.com/user-attachments/assets/dceebe1d-3aa2-4186-983a-fd5e2e0b9419)

SELECT *
FROM crime_scene_report
WHERE type = "murder";


SELECT *
FROM crime_scene_report
WHERE type = "murder"
AND date = 20180115
AND city = "SQL City";
![image](https://github.com/user-attachments/assets/19182670-8f82-408d-9eb2-6729c5a848a4)

SELECT *
FROM person
LIMIT 5;
![image](https://github.com/user-attachments/assets/c38a8289-3595-4241-ae06-a29a7856d36c)


SELECT *
FROM person
WHERE address_street_name = "Northwestern Dr"
ORDER BY address_number DESC;
![image](https://github.com/user-attachments/assets/01445fa8-410c-4a50-b39f-b96fd86371bc)


SELECT *
FROM person
WHERE name LIKE '%Annabel%'
AND address_street_name = "Franklin Ave";
![image](https://github.com/user-attachments/assets/dc64caea-71f3-4bb5-9d5c-1497e3c53f3f)


SELECT *
FROM interview
WHERE person_id IN ("14887", "16371");
![image](https://github.com/user-attachments/assets/70f2c6d2-fcd3-4187-bc74-a6fc16527af4)


SELECT *
FROM get_fit_now_check_in
WHERE membership_id LIKE '48Z%'
AND check_in_date = "20180109";
![image](https://github.com/user-attachments/assets/9bfaefc1-3506-4a5d-b995-0f587620ebcd)


SELECT *
FROM drivers_license
WHERE gender = "male"
AND plate_number LIKE '%H42W%';
![image](https://github.com/user-attachments/assets/f8cd3660-444d-460f-a737-ad3459c531dd)


SELECT *
FROM person
WHERE license_id IN ("423327", "664760");
![image](https://github.com/user-attachments/assets/3649aca4-6f6f-46be-a4a4-fed06f4fe188)


SELECT *
FROM get_fit_now_member
WHERE person_id IN ("51739", "67318");
![image](https://github.com/user-attachments/assets/07e4e7a0-d081-4264-b34d-2b126d5b4ce3)

INSERT INTO solution VALUES (1, 'Jeremy Bowers'); 
SELECT value FROM solution;
![image](https://github.com/user-attachments/assets/94237657-7d1f-490d-9a8d-11f7cb6528c8)


