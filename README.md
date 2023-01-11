# Query


SELECT format(CAST(SUM(a.WorkTimeInMin) as int) / 60 + (CAST(SUM(a.WorkTimeInMin) as int) % 60) / 100.0,'N','de-de') as 'Worked Hours'
  FROM [MyTest].[dbo].[Test] as a




SELECT CAST(SUM(a.WorkTimeInMin) as int) / 60
  FROM [MyTest].[dbo].[Test] as a




  SELECT (CAST(SUM(a.WorkTimeInMin) as int) % 60)/100.0
  FROM [MyTest].[dbo].[Test] as a

