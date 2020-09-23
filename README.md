<div align="center">

## asp date format dd/mm/yyyy


</div>

### Description

I looked for a way to format the date into dd/mm/yyyy server side. not much here so here is a one liner for those who need it.

<%

strcurrentdate = day(date) & "/" & month(date) & "/" & year(date)

response.write strcurrentdate

%>
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ken Edmonds](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ken-edmonds.md)
**Level**          |Beginner
**User Rating**    |4.2 (42 globes from 10 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ken-edmonds-asp-date-format-dd-mm-yyyy__4-7105/archive/master.zip)





### Source Code

```
<%
strcurrentdate = day(date) & "/" & month(date) & "/" & year(date)
response.write strcurrentdate
%>
```

