
* access plan manager
  * sqlra_cache_mem_please
    * Package cache overflow. Se ha excedido su tamaño máximo. Se recomienda poner en AUTOMATIC.
  * sqlra_resize_pckcache
    * Se ha cambiado el tamaño del package cache.
  * sqlra_statement_concentrator
    * Hay una situación con el statement concentrator.
* base sys utilities
  * sqeAgent::AgentBreathingPoint
    * ?
* bsu security
  * sqlexLogPluginMessage
    * Intento de conexión con password inválido.
* buffer pool services
  * sqlbAlterBufferPoolAct
    * Modificación de buffer automática.
  * sqlbCheckStateTransition
    * Se está haciendo una solicitud de cambio de estado, pero el estado actual no lo permite. Puede ser debido a un backup ejecutado mientras hay un reorg en ejecución.
  * sqlbTestSetDatapoolState
    * Se está haciendo una solicitud de cambio de estado, pero el estado actual no lo permite. Puede ser debido a un backup ejecutado mientras hay un reorg en ejecución.
* catalog services
  * sqlrlCatalogScan::fetch
    * ? Después de un deadlock, donde se hace rollback.
  * sqlrlCatalogScan::postUpdateCacheHandling
    * ? se recibió una interrupción.
  * sqlrlCatalogScan::update
    * ? se recibió una interrupción.
  * sqlrlDropIndex
    * ?
* common communication
  * sqlcctcptest
    * Se desconectó el client.
  * sqlcctest
    * ?
* config/install
  * sqlf_openfile
    * ?
  * sqlfLogUpdateCfgParam
    * Cambio de un parámetro de configuración.
* data management
  * sqldBeginIndexCreate
    * Comienzo de reconstrucción de un índice.
  * sqldColumnAlter
    * Cambio de propiedades en una tabla.
  * sqldEndIndexCreate
    * Índice reconstruido.
  * sqldEscalateLocks
    * Hubo una escalación de locks
  * sqldIndexCreate
    * Aviso de notificación de reconstrucción de índice en curso.
* data protection services
  * sqlpgArchiveLogFile
    * Inicio y finalización de archivado de log de transacciones.
  * sqlpgArchiveLogVendor
    * Problema para archivar log en sistema de archivado.
  * sqlpgolf
    * Problema con log de transacciones.
  * sqlpgReadXhdrFromFile
    * Problema con log de transacciones.
  * sqlpgRenameFileDuringLogReclaim
    * ? Borrando archivo por ser pequeño (log, se supone)
  * sqlpgRetrieveLogFile
    * Inicio y finalización de recuperación de log de transacciones desde el sistema de archivado.
  * sqlpgRetrieveLogVendor
    * Problema recuperando logs desde el sistema de archivado.
  * sqlpgRetryFailedArchive
    * Problema con el sistema de archivado.
  * sqlpOpenLogForBackup
    * El backup fue cancelado.
  * sqlpRestartVendorAPI
    * Libreria de archivado reiniciada.
  * sqlpWriteToVendorDevice
    * Problema archivando logs.
* database utilities
  * sqlubBuildAppTbsp
    * Problema accediendo un tablespace. Probablemente hay una operación de mantenimiento sobre este (reorg) y otra operación no puede comenzar (backup).
  * sqlubcka
    * Backup terminado.
  * sqlubCleanupPartialBackup
    * Borrado de imágenes de backup viejas. Puede que no lo pueda realizar si es en mecanismo externo.
  * sqlubDeleteVendorImage
    * Borrado de imágenes de backup viejas. Puede que no lo pueda realizar si es en mecanismo externo.
  * sqlubMWResponse
    * Problema con sistema de mecanismo externo de archivado.
  * sqlubProcessLogExtent
    * Problema incluyendo logs dentro del archivo de backup.
  * sqlubSetupJobControl
    * Comienzo de un backup.
  * sqlubTuneBuffers
    * Afinamiento del buffer para backup.
  * sqluMCWriteToDevice
    * Problema escribiendo a mecanismo de archivado.
  * sqluMapVend2MediaRCWithLog
    * Mapeado de librería de mecanismo de archivado.
  * sqluVendorCallWrapper
    * Envoltura de mecanismo externo.
  * sqluxGetAvailableHeapPages
    * Afinamiento del buffer para backup.
  * sqluxGetDegreeParallelism
    * Afinamiento del buffer para backup.
  * sqluxLogDataStats
    * Cálculo del tamaño del backup.
* DRDA Application Server
  * sqljsTermAgentReply
    * Se mataron las conexiones, sql1224.
* Health Monitor
  * db2HmonEvalReorg
    * Chequeo de health monitor para reorganización
  * HealthIndicator::update
    * Actualización de estado del Health Center.
* oper system services
  * sqloInvokeVendorFunction
    * Reiniciando mecanismo fenced.
  * sqloReadVendorRC
    * Reiniciando mecanismo fenced.
  * sqlossig
    * Matando proceso actual de mecanismo fenced.
* RAS/PD component
  * pdDiagArchiveDiagnosticLog
    * Generación de un nuevo archivo de log - db2diag.log
  * pdDiagReadFromFileIntoBufferBS
    * Problema asociado la lectura del db2diag.
  * pdDumpFencedVendorProcessInfo
    * Reinicio de fenced process. Cuando se reinicia la librería de logarchmeth.
  * pdLogInternal
    * Encabezado del archivo de logs - db2diag.log
* recovery manager
  * sqlplfrScanNext
    * ?
* relation data serv
  * sqlr_init_tstat
    * Analiza los valores actuales de ciertos parámetros.
  * sqlrr_rds_common_post
    * ? sql1224
  * sqlrreorg_table
    * Reorganización de tablas.
* routine_infrastructure
  * sqlerGetFmpThread
    * ? Error inesperado
  * sqlerMasterThreadListener
    * Manejado de threads. Cuando no hay espacio no puede crearlo para java.
  * sqlerMasterThreadReq
    * ? Problema creando thread
* Self tuning memory manager
  * stmmLog
    * Borrado del archivo de log del STMM.
  * stmmLogGetFileStats
    * Creación de un archivo para los logs de STMM.
* trace services
  * sqlt_logerr_data (secondary logging func
    * ?
