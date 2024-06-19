COUNT(
  CASE
    WHEN YEAR(Registro DI) = 2024 THEN 1
    ELSE NULL
  END
)

SUM(
  CASE 
    WHEN YEAR(Registro DI) = 2024 AND Modal = "Marítimo" THEN 1 
    ELSE 0 
  END
)

SUM(
  CASE 
    WHEN YEAR(Registro DI) = 2024 AND MONTH(Registro DI) <= 5 THEN 1 
    ELSE 0 
  END
)

CASE WHEN EXTRACT(YEAR FROM `Data Registro`) = 2023 THEN `Local Descarga - Total Dólares` ELSE 0 END

