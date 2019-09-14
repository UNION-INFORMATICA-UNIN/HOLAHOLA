# INSERT
HOLA MUNDO
/*
USE tempdb
GO
CREATE TABLE dbo.Opportunity
(
OpportunityID	int not null
				identity (1,1),
Requerements	nvarchar(50) not null,
ReciveDate		date not null,
LikelyClosing	date null,
SalesPersonID	int null,
Rating			int not null
)
insert into dbo.Opportunity
(	
Requerements  ,
ReciveDate	  ,
LikelyClosing ,
SalesPersonID ,
Rating		
)
VALUES
('N.D.',SYSDATETIME(),DATEADD(MONTH,1,SYSDATETIME()),34,9),
('N.D.',SYSDATETIME(),DATEADD(MONTH,1,SYSDATETIME()),37,2)


SELECT *
FROM Opportunity


insert into dbo.Opportunity
(	
Requerements  ,
ReciveDate	  ,
SalesPersonID ,
Rating		
)
VALUES
('N.D.',SYSDATETIME(),72,8)
*/
