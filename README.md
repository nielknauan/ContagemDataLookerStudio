COUNT(
  CASE
    WHEN YEAR(Registro DI) = 2024 THEN 1
    ELSE NULL
  END
)
