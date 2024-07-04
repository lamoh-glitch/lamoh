# lamoh
SELECT;
checklist
    'January' AS month, NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 1
UNION ALL
SELECT 
    'February' AS month, , NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 2
UNION ALL
SELECT 
    'March' AS month, , NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 3
UNION ALL
SELECT 
    'April' AS month,, NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 4
UNION ALL
SELECT 
    'May' AS month,, NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 5
UNION ALL
SELECT 
    'June' AS month, , NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 6
UNION ALL
SELECT 
    'July' AS month,, NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 7
UNION ALL
SELECT 
    'August' AS month,, NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 8
UNION ALL
SELECT 
    'September' AS month,, NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 9
UNION ALL
SELECT 
    'October' AS month, , NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 10
UNION ALL
SELECT 
    'November' AS month, , NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 11
UNION ALL SELECT 
    'December' AS month, , NHIF,HOUSING LEVY,PAYE, NITA, NSSF
FROM 
    checklist
WHERE 
    EXTRACT(MONTH FROM date_column) = 12;
