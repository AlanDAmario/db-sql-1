Quanti sono gli insegnanti che non hanno un numero di telefono?



SELECT
    COUNT(*) AS teachers_without_phone
FROM
    `teachers`
WHERE
    `phone` IS NUll;