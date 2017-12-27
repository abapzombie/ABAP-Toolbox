Classes to help with APO BAPIs. Consistent data accesses in APO are usually made by BAPIs that are in sync with APO's Live Cache and they are all called using the same basic code structure. These classes cover basic data retrieving and document deletion.

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


You can add the parameters as you want for each BAPI Method, just remember to set them as Opitional parameters, so you won't break any other development that is already using the class.