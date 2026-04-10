# Aviation-SQL-Journey
Daily SQL practice and aviation data projects
SELECT * FROM DOHA_AIRPORT_LIVE WHERE Origin = 'London' OR  Origin = 'Paris';
SELECT * FROM DOHA_AIRPORT_LIVE WHERE NOT Status = 'On-Time' ORDER BY Delay_Minutes  DESC;
SELECT COUNT(*) FROM DOHA_AIRPORT_LIVE WHERE Origin = 'Mumbai' AND Seats_Available > 15;
