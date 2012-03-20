Made by Mauricio Cruz
* Currently under development, may have bugs and the structure may change *

------------------------------------------------------------

Class to help with APO BAPIs. Currently the program covers basic data retrieving and dcument deletion. Consistent data accesses in APO is usually made by BAPIs that are in sync with APO's Live Cache. I was tired of making the same accesses again and again and again, so I code this out. 

------------------------------------------------------------

BAPI List:

BAPI_MOSRVAPS_DELEMULTI
BAPI_MOSRVAPS_GETLIST2
BAPI_PDSSRVAPS_GETLIST
BAPI_POSRVAPS_GETLIST3
BAPI_POSRVAPS_REMOVEITEMS
BAPI_PRDSRVAPS_SAVEMULTI2
BAPI_PROCRELATION_DELETEMULTI2
BAPI_PROCRELATION_GETLIST2
BAPI_QTASRVAPS_DELMULTI
BAPI_QTASRVAPS_GETLIST2
BAPI_SLSRVAPS_DELMULTI
BAPI_SLSRVAPS_GETLIST2

------------------------------------------------------------

You can add the parameters as you want for each BAPI Method, just remember to set them as Opitional parameters, so you won't break any other development that is already using the class.

------------------------------------------------------------

If you find any bugs or have any suggestion, don't hesitated to comment/push request/create bugs.

Enjoy!