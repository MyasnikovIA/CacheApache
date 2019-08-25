# CacheApache
<br>zn "%SYS"
<br>do $system.OBJ.Load("%ZWeb.Server.xml","c")
<br> d ##class(%ZWeb.Server).Start(80,"index.html") // Запустить сервер
<br> d ##class(%ZWeb.Server).Stop(80)               // Отсановит сервер
<br> 
<br> 
<br><script language="JavaScript" src="#($SYSTEM.CSP.GetDefaultApp($ZU(5)))#/#($zcvt("%ZWeb.RunJob","O","URL"))#.cls"></script>  
<br><script language="JavaScript" src="#($SYSTEM.CSP.GetDefaultApp($ZU(5)))#/#($zcvt("%ZWeb.RunJob","O","URL"))#.cls/?include=User.test"></script>
