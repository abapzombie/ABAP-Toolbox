:warning: _These codes were created 10+ years ago and are being kept here for reference purposes (tons of legacy code out there, right?). If you want to tackle any of these problems, you should first try looking for modern APIs on newer ABAP versions ([this](https://help.sap.com/http.svc/rc/abapdocu_752_index_htm/7.52/en-US/index.htm) is a good start)._

NUGG Files, SAPLink and ABAPGit
===============================

SAPLINK was one of the biggest open source projects from the ABAP community. Back then it was the only way a developer could copy whole ABAP projects from one system to another without involving a BASIS guy. You can check our SAPLINK's legacy on their website: http://saplink.org .

However, since a few years back the ABAP community has turned its attention to a better way of sharing code between systems: **ABAPGit** https://github.com/larshp/abapGit . You should definitely use ABAPGit instead of SAPLINK whenever possible (aka the SAP infrascture guys didn't get in your way).

I'm not working with ABAP anymore, so I have no access to a SAP system to convert the libraries here from .NUGG files to the ABAPGit structure. Therefore, if you want to use any of the codes here you'll have to use SAPLink to port them to your SAP system.
