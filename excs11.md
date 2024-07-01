Eliminare dalla tabella studenti il record creato precedentemente al punto 9;


DELETE FROM `students`
WHERE `name` = 'Tuonome'
AND `surname` = 'Tuocognome'
AND `date_of_birth` = '1990-01-01'
AND `email` = 'tuoemail@example.com'
AND `phone_number` = '1234567890';


ecc.