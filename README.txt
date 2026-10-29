Experiment 9: Placement Dashboard using Data Controls & Crystal Reports

Files separated from the supplied PDF:
1. Default.aspx
2. Default.aspx.cs
3. Report.aspx
4. Report.aspx.cs

Important setup notes:
- The PDF source uses ASP.NET Web Forms and System.Data.SqlClient (SQL Server).
- Default.aspx.cs expects a connection string named "PlacementConnection" in Web.config.
- It expects a SQL Server table named "Placements".
- Report.aspx.cs expects the Crystal Reports file at:
  ~/Reports/PlacementReport.rpt
- Crystal Reports runtime/reference and the CrystalReportViewer control registration
  must be configured in the ASP.NET project before Report.aspx will run.
- The PDF does not provide the Web.config, SQL table creation script, or the
  PlacementReport.rpt file, so those are not included in this ZIP.

The code has been formatted and obvious OCR/typing issues from the PDF have been
cleaned up. Check control names and project configuration when integrating it.
