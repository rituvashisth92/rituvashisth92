# rituvashisth92

How to Run 



===========================To Run DB Mail===========================================
sp_configure 'show advanced options', 1;
GO
RECONFIGURE;
GO
 
sp_configure 'Database Mail XPs', 1;
GO
RECONFIGURE
GO
 
===================to Automate OLE AUTOMATION=====================================

sp_configure 'show advanced options', 1 

GO 
RECONFIGURE; 
GO 
sp_configure 'Ole Automation Procedures', 1 
GO 
RECONFIGURE; 
GO 
sp_configure 'show advanced options', 1 
GO 
RECONFIGURE;
