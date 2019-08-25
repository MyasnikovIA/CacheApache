# CacheApache
<br>zn "%SYS"
<br>do $system.OBJ.Load("%ZWeb.Server.xml","c")
<br> d ##class(%ZWeb.Server).Start(80,"index.html") // Запустить сервер
<br> d ##class(%ZWeb.Server).Stop(80)               // Отсановит сервер
<example>
   d ##class(%ZWeb.Server).Start(80,"D:\!!ProjectWor\Sirius\InstallSirena(26-04-2019)\env","index.html")
   d ##class(%ZWeb.Server).Start(80,"D:\AppServ\www","index.html")
   d ##class(%ZWeb.Server).Stop(80)
   d ##class(%ZWeb.Server).Stop()
</example>
<br> 
<br> 
<br><script language="JavaScript" src="#($SYSTEM.CSP.GetDefaultApp($ZU(5)))#/#($zcvt("%ZWeb.RunJob","O","URL"))#.cls"></script>  
<br><script language="JavaScript" src="#($SYSTEM.CSP.GetDefaultApp($ZU(5)))#/#($zcvt("%ZWeb.RunJob","O","URL"))#.cls/?include=User.test"></script>
