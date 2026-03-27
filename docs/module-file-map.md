# Module File Map
<!-- MODULE_FILE_MAP_START -->
app/cbl/COSGN00C.cbl = sign-on
app/bms/COSGN00.bms = sign-on
app/cpy-bms/COSGN00.CPY = sign-on

app/cbl/COMEN01C.cbl = main-menu
app/bms/COMEN01.bms = main-menu
app/cpy-bms/COMEN01.CPY = main-menu
app/cpy/COCOM01Y.cpy = main-menu

app/cbl/COACTVWC.cbl = account-management
app/cbl/COACTUPC.cbl = account-management
app/bms/COACTVW.bms = account-management
app/bms/COACTUP.bms = account-management
app/cpy-bms/COACTVW.CPY = account-management
app/cpy-bms/COACTUP.CPY = account-management
app/cpy/CVACT01Y.cpy = account-management, credit-card-management, transaction-management, bill-payment, authorization, mq-integration
app/cpy/CVACT03Y.cpy = account-management, credit-card-management

app/cbl/COCRDLIC.cbl = credit-card-management
app/cbl/COCRDSLC.cbl = credit-card-management
app/cbl/COCRDUPC.cbl = credit-card-management
app/bms/COCRDLI.bms = credit-card-management
app/bms/COCRDSL.bms = credit-card-management
app/bms/COCRDUP.bms = credit-card-management
app/cpy-bms/COCRDLI.CPY = credit-card-management
app/cpy-bms/COCRDSL.CPY = credit-card-management
app/cpy-bms/COCRDUP.CPY = credit-card-management
app/cpy/CVACT02Y.cpy = credit-card-management, authorization

app/cbl/COTRN00C.cbl = transaction-management
app/cbl/COTRN01C.cbl = transaction-management
app/cbl/COTRN02C.cbl = transaction-management
app/bms/COTRN00.bms = transaction-management
app/bms/COTRN01.bms = transaction-management
app/bms/COTRN02.bms = transaction-management
app/cpy-bms/COTRN00.CPY = transaction-management
app/cpy-bms/COTRN01.CPY = transaction-management
app/cpy-bms/COTRN02.CPY = transaction-management
app/cpy/CVTRA05Y.cpy = transaction-management, batch-processing
app/cpy/CVTRA06Y.cpy = transaction-management, batch-processing
app/cpy/CVTRA03Y.cpy = transaction-management, transaction-type-management
app/cpy/CVTRA04Y.cpy = transaction-management, reporting

app/cbl/CORPT00C.cbl = reporting
app/cbl/CBTRN03C.cbl = reporting, batch-processing
app/bms/CORPT00.bms = reporting
app/cpy-bms/CORPT00.CPY = reporting
app/cpy/CVTRA01Y.cpy = reporting, batch-processing
app/cpy/CVTRA02Y.cpy = reporting, batch-processing

app/cbl/COBIL00C.cbl = bill-payment
app/bms/COBIL00.bms = bill-payment
app/cpy-bms/COBIL00.CPY = bill-payment

app/cbl/COADM01C.cbl = user-management
app/cbl/COUSR00C.cbl = user-management
app/cbl/COUSR01C.cbl = user-management
app/cbl/COUSR02C.cbl = user-management
app/cbl/COUSR03C.cbl = user-management
app/bms/COADM01.bms = user-management
app/bms/COUSR00.bms = user-management
app/bms/COUSR01.bms = user-management
app/bms/COUSR02.bms = user-management
app/bms/COUSR03.bms = user-management
app/cpy-bms/COADM01.CPY = user-management
app/cpy-bms/COUSR00.CPY = user-management
app/cpy-bms/COUSR01.CPY = user-management
app/cpy-bms/COUSR02.CPY = user-management
app/cpy-bms/COUSR03.CPY = user-management
app/cpy/CSUSR01Y.cpy = user-management, sign-on

app/cbl/CBTRN01C.cbl = batch-processing
app/cbl/CBTRN02C.cbl = batch-processing
app/cbl/CBACT01C.cbl = batch-processing
app/cbl/CBACT02C.cbl = batch-processing
app/cbl/CBACT03C.cbl = batch-processing
app/cbl/CBACT04C.cbl = batch-processing
app/cbl/CBSTM03A.CBL = batch-processing
app/cbl/CBSTM03B.CBL = batch-processing
app/cbl/CBCUS01C.cbl = batch-processing
app/cbl/CBIMPORT.cbl = batch-processing
app/cbl/CBEXPORT.cbl = batch-processing
app/cbl/COBSWAIT.cbl = batch-processing
app/cbl/CSUTLDTC.cbl = batch-processing
app/asm/COBDATFT.asm = batch-processing
app/asm/MVSWAIT.asm = batch-processing
app/jcl/** = batch-processing
app/proc/** = batch-processing
app/scheduler/** = batch-processing
app/cpy/COSTM01.CPY = batch-processing
app/cpy/CSUTLDPY.cpy = batch-processing
app/cpy/CSUTLDWY.cpy = batch-processing
app/cpy/CVCUS01Y.cpy = batch-processing, account-management

app/app-authorization-ims-db2-mq/cbl/COPAUA0C.cbl = authorization
app/app-authorization-ims-db2-mq/cbl/COPAUS0C.cbl = authorization
app/app-authorization-ims-db2-mq/cbl/COPAUS1C.cbl = authorization
app/app-authorization-ims-db2-mq/cbl/COPAUS2C.cbl = authorization
app/app-authorization-ims-db2-mq/cbl/CBPAUP0C.cbl = authorization
app/app-authorization-ims-db2-mq/cbl/DBUNLDGS.CBL = authorization
app/app-authorization-ims-db2-mq/cbl/PAUDBLOD.CBL = authorization
app/app-authorization-ims-db2-mq/cbl/PAUDBUNL.CBL = authorization
app/app-authorization-ims-db2-mq/bms/** = authorization
app/app-authorization-ims-db2-mq/cpy/** = authorization
app/app-authorization-ims-db2-mq/cpy-bms/** = authorization
app/app-authorization-ims-db2-mq/ims/** = authorization
app/app-authorization-ims-db2-mq/ddl/** = authorization
app/app-authorization-ims-db2-mq/dcl/** = authorization
app/app-authorization-ims-db2-mq/jcl/** = authorization

app/app-transaction-type-db2/cbl/COTRTLIC.cbl = transaction-type-management
app/app-transaction-type-db2/cbl/COTRTUPC.cbl = transaction-type-management
app/app-transaction-type-db2/cbl/COBTUPDT.cbl = transaction-type-management
app/app-transaction-type-db2/bms/** = transaction-type-management
app/app-transaction-type-db2/cpy/** = transaction-type-management
app/app-transaction-type-db2/cpy-bms/** = transaction-type-management
app/app-transaction-type-db2/ddl/** = transaction-type-management
app/app-transaction-type-db2/dcl/** = transaction-type-management
app/app-transaction-type-db2/jcl/** = transaction-type-management

app/app-vsam-mq/cbl/COACCT01.cbl = mq-integration
app/app-vsam-mq/cbl/CODATE01.cbl = mq-integration

app/cpy/COCOM01Y.cpy = main-menu, sign-on
app/cpy/CSMSG01Y.cpy = sign-on, account-management, credit-card-management, transaction-management, user-management
app/cpy/CSMSG02Y.cpy = sign-on, account-management, user-management
app/cpy/CSDAT01Y.cpy = batch-processing, transaction-management
app/cpy/CSLKPCDY.cpy = transaction-management, reporting
app/cpy/CSSETATY.cpy = account-management, credit-card-management, transaction-management
app/cpy/CSSTRPFY.cpy = account-management, credit-card-management, transaction-management
app/cpy/COTTL01Y.cpy = main-menu, sign-on
app/cpy/COADM02Y.cpy = user-management
app/cpy/COMEN02Y.cpy = main-menu
app/cpy/CODATECN.cpy = batch-processing
app/cpy/CUSTREC.cpy = batch-processing, account-management
app/cpy/CVEXPORT.cpy = batch-processing
<!-- MODULE_FILE_MAP_END -->
