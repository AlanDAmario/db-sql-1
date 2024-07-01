Inserire nella tabella degli studenti un nuovo record con i propri dati (per il campo
degree_id, inserire un valore casuale);


INSERT INTO `students` (`name`, `surname`, `date_of_birth`, `email`, `enrolment_date`, `fiscal_code` `degree_id`)
VALUES ('Gaetano', 'Frascolla', '1990-01-01', 'gaetano.frascolla@example.com', '2024-07-01', 'FFXDDX99L01C632F', FLOOR(1 + (RAND() * 10)));
