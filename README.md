# SQL Server KIT
Useful links, scripts, tools and best practice for Microsoft SQL Server Database

Headers:
 - [Repo folders and files](#repo-folders-and-files)
 - [SQL Server Web Resources](#sql-server-web-resources)
 - [SQL Server Express direct download links](#sql-server-express-direct-download-links)
 - [Microsoft Adventure Works Sample Databases download links](#microsoft-adventure-works-sample-databases-download-links)
 - [Microsoft Transact-SQL Hints](#microsoft-transact-sql-hints)
 - [PowerShell and SQL Server](#powershell-and-sql-server)
 - [TSQL format code](#tsql-format-code)
 - [Free SQL Server ebooks](#free-sql-server-ebooks)


## Repo folders and files
 - [SQL Server Name Convention](/SQL Server Name Convention.md)
 - [SQL Server Edition](/SQL Server Edition.md)
 - [SQL Server People](/SQL Server People.md 'Most Valuable SQL Server professionals')
 - [SQL Server Trace Flag](/SQL Server Trace Flag.md 'Complete list from many resources - 162 Trace Flags') (Complete list - 162 trace flags)
 - [SQL Server Version](/SQL Server Version.md 'List of all version Microsoft SQL Sever') (Complete list - from SQL Server 1.0 to SQL Server 2016)
 - [Articles](/Articles)
 - [Base line Collector script](/BaselineCollector) (by Robert Virag)
 - [CLR procedures](/CLR)
    - [SQL#](/CLR/SQLsharp_SETUP.sql) free version - QUICKEST and EASIEST way to extending the power of T-SQL with C#
    - [SplitterB_CLR](/CLR/SplitterB_CLR.sql)
 - [dbWarden](/dbWarden) a free SQL Server Monitoring Package (by Stevie Rounds and Michael Rounds)
 - [Known Errors](/Errors)
 - [Ola Maintenance Solution] (by Ola Hallengren)
 - [SSMS addons](/SSMS_addons)
    - [SSMSBoost add-in](/SSMS_addons#ssmsboost 'Adds missing features and improves your productivity')
    - [SQL Code Guard](/SSMS_addons#sql-code-guard 'Provides fast and comprehensive static analysis for T-Sql code, shows code complexity and objects dependencies')
    - [SQL Search](/SSMS_addons#sql-search 'Free add-in from Red Gate that lets you quickly search for SQL across your databases')
    - [SQL Scripts Manager](/SSMS_addons#sql-scripts-manager 'Powerful and reliable scripts written by SQL Server experts')
    - [Supratimas](/SSMS_addons#supratimas 'SQL Server query execution visualizer')
    - [dbForge SQL Complete](/SSMS_addons#dbforge-sql-complete)
    - [SSMS Tools Pack](/SSMS_addons#ssms-tools-pack)
    - [SQL Pretty Printer](/SSMS_addons#sql-pretty-printer)
    - [SQL Sentry Plan Explorer](/SSMS_addons#sql-sentry-plan-explorer)
    - [TSQL Code Smells Finder](/SSMS_addons#tsql-code-smells-finder)
    - [SQLTreeo](/SSMS_addons#sqltreeo)
    - [ApexSQL Complete](/SSMS_addons#apexsql-complete)
    - [ApexSQL Refactor](/SSMS_addons#apexsql-refactor)
    - [ApexSQL Search](/SSMS_addons#apexsql-search)
    - [Spotlight Developer](/SSMS_addons#spotlight-developer)
    - [dbForge Source Control](/SSMS_addons#dbforge-source-control)
    - [dbForge Unit Test](/SSMS_addons#dbforge-unit-test)
    - [dbForge Data Pump](/SSMS_addons#dbforge-data-pump)
    - [dbForge Index Manager](/SSMS_addons#dbforge-index-manager)
    - [dbForge Object Search](/SSMS_addons#dbforge-object-search)
 - [Useful scripts](/Scripts)
    - **Awesome SQL Server Diagnostic Information Queries** (by Glenn Alan Berry)
      - [SQL Server 2016 Diagnostic Information Queries](/Scripts/SQL Server 2016 Diagnostic Information Queries.sql)
      - [SQL Server 2014 Diagnostic Information Queries](/Scripts/SQL Server 2014 Diagnostic Information Queries.sql)
      - [SQL Server 2012 Diagnostic Information Queries](/Scripts/SQL Server 2012 Diagnostic Information Queries.sql)
      - [SQL Server 2008 R2 Diagnostic Information Queries](/Scripts/SQL Server 2008 R2 Diagnostic Information Queries.sql)
      - [SQL Server 2008 Diagnostic Information Queries](/Scripts/SQL Server 2008 Diagnostic Information Queries.sql)
    - [Table count alternative](/Scripts/Table Count alternative.sql) (by Jes Schultz Borland)
    - [Foreign Key batch rename](/Scripts/Foreign Key batch rename.sql) (by Wes Henriksen)
    - [Count character matches](/Scripts/Count character matches.sql)
    - and many others...
 - [SSMS snippets](/Snippets)
 - [Stored Procedure](/Stored_Procedure)
   - [sp_DBPermissions](/Stored_Procedure/sp_DBPermissions.sql) (by Kenneth Fisher)
   - [sp_SrvPermissions](/Stored_Procedure/sp_SrvPermissions.sql) (by Kenneth Fisher)
   - [usp_who5](/Stored_Procedure/usp_who5.sql) (by Sean Smith)
   - [usp_String_Search](/Stored_Procedure/usp_String_Search.sql) (by Sean Smith)
   - [usp_BulkUpload](/Stored_Procedure/usp_BulkUpload.sql)
   - [usp_TableUnpivot](/Stored_Procedure/usp_TableUnpivot.sql)
   - and many others...
 - [User Defined Function](/User_Defined_Function)
    - [udf_parseJSON](/User_Defined_Function/udf_parseJSON.sql)
    - [udf_RenderXMLToString](/User_Defined_Function/udf_RenderXMLToString.sql)
    - [udf_RTF2Text](/User_Defined_Function/udf_RTF2Text.sql)
    - [udf_SplitStringByDelimiter](/User_Defined_Function/udf_SplitStringByDelimiter.sql)
    - [udf_Tally](/User_Defined_Function/udf_Tally.sql)
    - and many others...
 - [Utilities](/Utilities)
    - [tablediff Utility](/Utilities#tablediff-utility)
    - [Microsoft Log Parser](/Utilities#microsoft-log-parser)
    - [Diskspd](/Utilities#diskspd)
    - [HammerDB](/Utilities#hammerdb)
    - [dta Utility](/Utilities#dta-utility)
    - [osql Utility](/Utilities#osql-utility)
    - [sqldiag Utility](/Utilities#sqldiag-utility)
    - [sqldumper Utility](/Utilities#sqldumper-utility)
    - [SqlLocalDB Utility](/Utilities#sqllocaldb-utility)
    - [sqllogship Utility](/Utilities#sqllogship-utility)
    - [sqlservr Application](/Utilities#sqlservr-application)
    - [SQL XEvent Profiler](/Utilities#sql-xevent-profiler)
    - [DLM Dashboard](/Utilities#dlm-dashboard)
    - [SQL DBA Bundle](/Utilities#sql-dba-bundle)
    - [SQL Check](/Utilities#sql-check)
    - [SQL Fragmentation Analyzer](/Utilities#sql-fragmentation-analyzer)
    - [SQL Heat Map](/Utilities#sql-heat-map)
    - [SQL Hekaton Memory Check](/Utilities#sql-hekaton-memory-check)
    - [SQL Page Viewer](/Utilities#sql-page-viewer)
    - [SQL Update Statistics](/Utilities#sql-update-statistics)
    - [SQL Statistics Aggregator](/Utilities#sql-statistics-aggregator)
    - [SQL Backup Status Reporter](/Utilities#sql-backup-status-reporter)
    - [SQL Integrity Check](/Utilities#sql-integrity-check)
    - [SQL Job Manager](/Utilities#sql-job-manager)
    - [Azure SQL Database Backup](/Utilities#azure-sql-database-backup)
    - [SQL Column Search](/Utilities#sql-column-search)
    - [SQL Permissions Extractor](/Utilities#sql-permissions-extractor)
    - [dbForge Schema Compare](/Utilities#dbforge-schema-compare)
    - [dbForge Data Compare](/Utilities#dbforge-data-compare)    
    - [dbForge Data Generator](/Utilities#dbforge-data-generator)
    - [dbForge Query Builder](/Utilities#dbforge-query-builder)  
    - [dbForge Event Profiler](/Utilities#dbforge-event-profiler)
    - [dbForge SQL Decryptor](/Utilities#dbforge-SQL-decryptor)  


## SQL Server Web Resources
 - Blogs
    - [SQL Central Blog Scripts](http://www.sqlservercentral.com/Scripts/)
    - [SQL Central Blog Articles](http://www.sqlservercentral.com/Articles/)
    - [SQL Central Blog Stairways](http://www.sqlservercentral.com/stairway/)
    - [MSSQLTips](https://www.mssqltips.com/get-free-sql-server-tips/)
    - Awesome [BRENT OZAR] scripts, videos and articles
    - [Glenn Berry's SQL Server Performance]
    - [Kenneth Fisher SQLStudies Blog](http://sqlstudies.com/)
    - [Best SQL Server Perfomance Blog](http://sqlperformance.com/)
    - Best backup and index maintenance solution [Ola Maintenance Solution]
    - [Weblogs SQLTeam Blogs](http://weblogs.sqlteam.com/)
 - Free Videos
   - [IDERA Resource Center](https://www.idera.com/resourcecentral)
   - [MSSQLTips SQL Server Webcasts and Videos](https://www.mssqltips.com/sql-server-webcasts/)
   - [SQL Server Videos](http://www.sqlservervideos.com/)
   - [TECHNET How do I Videos](https://technet.microsoft.com/en-us/library/dd353197.aspx)
   - [Veeam Learn Microsoft SQL Server](http://go.veeam.com/learn-microsoft-sql-server-free-video-tutorial-course.html)
 - Free Database Podcasts
   - [SQL Server Radio](http://www.sqlserverradio.com/)
   - [SQL Data Partners](http://sqldatapartners.com/podcast/)
   - [Away from the Keyboard](http://awayfromthekeyboard.com/)
 - Other
    - [SQL Server Management Studio] installation download link
    - [SQL# CLR functions](http://www.sqlsharp.com/)
    - [SSIS Performance Benchmarks](http://ssisperformance.com/)


## SQL Server Express direct download links
Original post written by Scott Hanselman: http://www.hanselman.com/blog/DownloadSQLServerExpress.aspx<br />
Official Microsoft SQL Server Express page: https://www.microsoft.com/en-us/server-cloud/products/sql-server-editions/sql-server-express.aspx


### [Download SQL Server 2014 Express](http://www.microsoft.com/en-us/download/details.aspx?id=42299)
You likely just want SQL Server 2014 Express with Tools. This download includes SQL Management Studio:
 - [SQL Server 2014 Express x64](http://download.microsoft.com/download/E/A/E/EAE6F7FC-767A-4038-A954-49B8B05D04EB/ExpressAndTools%2064BIT/SQLEXPRWT_x64_ENU.exe)
 - [SQL Server 2014 Express x86](http://download.microsoft.com/download/E/A/E/EAE6F7FC-767A-4038-A954-49B8B05D04EB/ExpressAndTools%2032BIT/SQLEXPRWT_x86_ENU.exe)

Here's just SQL Server 2014 Management Studio:
 - [SQL Management Studio x64](http://download.microsoft.com/download/E/A/E/EAE6F7FC-767A-4038-A954-49B8B05D04EB/MgmtStudio%2064BIT/SQLManagementStudio_x64_ENU.exe)
 - [SQL Management Studio x86](http://download.microsoft.com/download/E/A/E/EAE6F7FC-767A-4038-A954-49B8B05D04EB/MgmtStudio%2032BIT/SQLManagementStudio_x86_ENU.exe)

SQL Server 2014 Express with Advanced Services:
 - [Advanced Services x64](http://download.microsoft.com/download/E/A/E/EAE6F7FC-767A-4038-A954-49B8B05D04EB/ExpressAdv%2064BIT/SQLEXPRADV_x64_ENU.exe)
 - [Advanced Services x86](http://download.microsoft.com/download/E/A/E/EAE6F7FC-767A-4038-A954-49B8B05D04EB/ExpressAdv%2032BIT/SQLEXPRADV_x86_ENU.exe)


### [Download SQL Server 2012 Express](http://www.microsoft.com/en-us/download/details.aspx?id=29062)
You likely just want SQL Server 2012 Express with Tools. This download includes SQL Management Studio:
 - [SQL Server 2012 Express x64](http://download.microsoft.com/download/8/D/D/8DD7BDBA-CEF7-4D8E-8C16-D9F69527F909/ENU/x64/SQLEXPRWT_x64_ENU.exe)

Here's just SQL Server 2012 Management Studio:
 - [SQL Management Studio x64](http://download.microsoft.com/download/8/D/D/8DD7BDBA-CEF7-4D8E-8C16-D9F69527F909/ENU/x64/SQLManagementStudio_x64_ENU.exe)
 - [SQL Management Studio x86](http://download.microsoft.com/download/8/D/D/8DD7BDBA-CEF7-4D8E-8C16-D9F69527F909/ENU/x86/SQLManagementStudio_x86_ENU.exe)


### [Download SQL Server 2008 Express R2 SP2](http://www.microsoft.com/en-us/download/details.aspx?id=30438)
You likely just want SQL Server 2008 Express with Tools. This download includes SQL Management Studio:
 - [SQL Server 2008 Express x64](http://download.microsoft.com/download/0/4/B/04BE03CD-EAF3-4797-9D8D-2E08E316C998/SQLEXPRWT_x64_ENU.exe)
 - [SQL Server 2008 Express x86](http://download.microsoft.com/download/0/4/B/04BE03CD-EAF3-4797-9D8D-2E08E316C998/SQLEXPRWT_x86_ENU.exe)

Here's just SQL Server 2008 Management Studio:
 - [SQL Management Studio x64](http://download.microsoft.com/download/0/4/B/04BE03CD-EAF3-4797-9D8D-2E08E316C998/SQLManagementStudio_x64_ENU.exe)
 - [SQL Management Studio x86](http://download.microsoft.com/download/0/4/B/04BE03CD-EAF3-4797-9D8D-2E08E316C998/SQLManagementStudio_x86_ENU.exe)


### [Download SQL Server 2005 Express](https://www.microsoft.com/en-us/download/details.aspx?id=21844)


## Microsoft Adventure Works Sample Databases download links
 - [Microsoft SQL Server Community Projects & Samples](http://sqlserversamples.codeplex.com/)
 - [Adventure Works Sample Databases and Scripts for SQL Server 2016 CTP3](http://www.microsoft.com/en-us/download/details.aspx?id=49502)
 - [Adventure Works 2014 Sample Databases](https://msftdbprodsamples.codeplex.com/releases/view/125550)
 - [Adventure Works 2012 Sample Databases](http://msftdbprodsamples.codeplex.com/releases/view/55330)
 - [Microsoft SQL Server 2008 R2 SR1 Sample Databases](https://sqlserversamples.codeplex.com/releases/view/72278)


## [Microsoft Transact-SQL Hints](https://msdn.microsoft.com/en-us/library/ms187713.aspx)
 - [Transact-SQL Join Hints](https://msdn.microsoft.com/en-us/library/ms173815.aspx)
 - [Transact-SQL Table Hints](https://msdn.microsoft.com/en-us/library/ms187373.aspx)
 - [Transact-SQL Query Hints](https://msdn.microsoft.com/en-us/library/ms181714.aspx)


## PowerShell and SQL Server
 - [SQL Server & Windows Documentation Using Windows PowerShell](https://sqlpowerdoc.codeplex.com/) (by Kendal Vandyke)
 - [TSQL Code Smells Finder](https://tsqlsmells.codeplex.com/) (by Dave Ballantyne)
 - [Stairway to SQL PowerShell](http://www.sqlservercentral.com/stairway/91327/) (by Ben Miller)
 - [SQL Server Health Check Script with Powershell](http://www.codeproject.com/Tips/848661/SQL-Server-Health-Check-Script-with-Powershell) (by Atul_Kapoor)


## TSQL format code
 - http://www.dpriver.com/pp/sqlformat.htm
 - http://stackoverflow.com/questions/401928/sql-formatter-for-sql-management-studio
 - http://www.apexsql.com/sql_tools_refactor.aspx
 - http://poorsql.com/
 - http://www.architectshack.com/PoorMansTSqlFormatter.ashx
 - http://www.ssmstoolspack.com/
 - http://www.devart.com/dbforge/sql/sqlcomplete/
 - http://www.sql-format.com/


## Free SQL Server ebooks
 - [Avesome Red Gate ebooks](http://www.red-gate.com/community/books/)
 - [Microsoft large collection](https://blogs.msdn.microsoft.com/mssmallbiz/2012/07/27/large-collection-of-free-microsoft-ebooks-for-you-including-sharepoint-visual-studio-windows-phone-windows-8-office-365-office-2010-sql-server-2012-azure-and-more/)
 - [OnlineVideoLectures ebooks](http://onlinevideolecture.com/ebooks/?subject=SQL-Server)
 - [Brent Ozar ebooks](http://www.brentozar.com/first-aid/free-database-books-pdfs-download/)
 - [E-books Directory](http://www.e-booksdirectory.com/listing.php?category=569)
 - [TOAD SQL Server ebooks](https://www.toadworld.com/platforms/sql-server/b/weblog/archive/2013/06/21/huge-collection-of-free-microsoft-sql-server-ebooks)


[BRENT OZAR]:http://www.brentozar.com/
[Glenn Berry's SQL Server Performance]:http://sqlserverperformance.wordpress.com/
[Ola Maintenance Solution]:http://ola.hallengren.com/
[SQL Server Management Studio]:https://msdn.microsoft.com/en-us/library/mt238290.aspx
