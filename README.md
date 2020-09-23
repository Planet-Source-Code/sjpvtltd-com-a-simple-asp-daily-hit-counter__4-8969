<div align="center">

## A simple ASP Daily Hit Counter


</div>

### Description

It shows Number of daily visitors or users to your site.
 
### More Info
 
Is application variable working on your Web Server or IIS?

No. of Daily Visiters Or Users


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SJPVTLTD\.COM](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sjpvtltd-com.md)
**Level**          |Advanced
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |ASP \(Active Server Pages\), HTML
**Category**       |[Server Side](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/server-side__4-31.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sjpvtltd-com-a-simple-asp-daily-hit-counter__4-8969/archive/master.zip)

### API Declarations

Copyright © 2003-2004 efreedownloads.com


### Source Code

```
<%
Dim x, y, temp, serv, D, hits
x = Trim(day(date()))
D = Application( "serv" )
   If D = x Then
      Application( "hits" ) = Application( "hits" ) + 1
    Else
      Application( "hits" ) = 1
   End If
   y = x
   temp = y
   Application( "serv" ) = temp
%>
There have been <%=Application( "hits" )%> hits to this page today!
```

