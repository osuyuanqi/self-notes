- the browser that displays the ASP file doesn't need to support scripting, since the script is executed on the server side.
- @{C# code}-> Razor view engine,cshtml, MVC3,4,5; <% C# .net code %>->MVC1,2,3,4
- viewbag->pass data from controller to view, save object into viewbag.
- ActionResult: return type could decide what received, such as Content(plain/text), File(filename,"application/pdf"). 
- route: default->/{Controller}/{Action}/{id}, e.g. /home/getempid?id=1 (right);/home/getempid/id/1 (wrong)
- Get: used to retrieve data, query in the address, can send limited characters; Post-> insert/delete/update operations, parameter in the "request body",unlimited characters.


====
why ASP.NET: Cross Platform, productive components, open source
