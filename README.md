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
