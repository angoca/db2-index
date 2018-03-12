
* access plan manager
  * sqlra_cache_mem_please
    * Package cache overflow. Se ha excedido su tamaño máximo. Se recomienda poner en AUTOMATIC.
  * sqlra_resize_pckcache
    * Se ha cambiado el tamaño del package cache.
  * sqlra_statement_concentrator
    * Hay una situación con el statement concentrator.
* base sys utilities
  * DB2main
    * ?
  * DB2StartMain
    * ?
  * sqeAgent::AgentBreathingPoint
    * ?
  * sqeApplication::AppStartUsing
    * ?
  * sqeLocalDatabase::FirstConnect
    * Estado activado de la base de datos.
  * sqeLocalDatabase::FreeResourcesOnDBShutdown
    * ?
  * sqeLocalDatabase::StartBackgroundAgents
    * ?
  * sqeLocalDatabase::TermDbConnect
    * Estado desactivado de la base de datos.
  * sqleCalculateDbHeaps
    * ?
  * sqleChildCrashHandler
    * ?
  * sqledint
    * ?
  * sqleGetStStLockFile
    * ?
  * sqleIssueStartStop
    * ?
  * sqleReleaseStStLockFile
    * ?
  * sqleRollupCacheALInfo
    * ?
  * sqleStartStopSingleNode
    * ?
* bsu security
  * sqlexLogPluginMessage
    * Intento de conexión con password inválido.
* buffer pool services
  * sqlbAlterBufferPoolAct
    * Modificación de buffer automática.
  * sqlbCheckStateTransition
    * Se está haciendo una solicitud de cambio de estado, pero el estado actual no lo permite. Puede ser debido a un backup ejecutado mientras hay un reorg en ejecución.
  * sqlbCleanupBeforeTerm
    * ?
  * sqlbDumpEventRecorder
    * ?
  * sqlbTestSetDatapoolState
    * Se está haciendo una solicitud de cambio de estado, pero el estado actual no lo permite. Puede ser debido a un backup ejecutado mientras hay un reorg en ejecución.
* catalog services
  * sqlrlCatalogScan::deleteRows
    * ?
  * sqlrlCatalogScan::fetch
    * ? Después de un deadlock, donde se hace rollback.
  * sqlrlCatalogScan::postUpdateCacheHandling
    * ? se recibió una interrupción.
  * sqlrlCatalogScan::update
    * ? se recibió una interrupción.
  * sqlrlDropIndex
    * ?
* Columnar Data Engine
  * cdeStartup
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
  * sqlpCloseVendorDevice
    * ?
  * sqlpgArchiveLogFile
    * Inicio y finalización de archivado de log de transacciones.
  * sqlpgArchiveLogVendor
    * Problema para archivar log en sistema de archivado.
  * sqlpgArchivePendingLogs
    * ?
  * sqlpghck
    * ?
  * sqlpgolf
    * Problema con log de transacciones.
  * sqlpgOpenLogExtent
    * ?
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
  * sqlpgSwitchProcessAllLogStreams
    * ?
  * sqlpinit
    * ?
  * sqlpOpenLogForBackup
    * El backup fue cancelado.
  * sqlpParallelRecoveryCalculateShredderScanMemory
    * ?
  * sqlpProgMonRecEndLastPhaseAndCompleteJob
    * ?
  * sqlpRestartVendorAPI
    * Libreria de archivado reiniciada.
  * sqlpSetRecoveryStartingPoint
    * ?
  * sqlpshrProcessLogChainsInXHDR
    * ?
  * sqlpshrSetInitialLogChain
    * ?
  * sqlptintMore
    * ?
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
  * sqluCheckIfAgentInterrupted
    * ?
  * sqluFencedVendorCBTerminate
    * ?
  * sqluMapVend2MediaRCWithLog
    * ?
  * sqluMCWriteToDevice
    * Problema escribiendo a mecanismo de archivado.
  * sqluMapVend2MediaRCWithLog
    * Mapeado de librería de mecanismo de archivado.
  * sqluReadBufferFromQueue
    * ?
  * sqluReadMessageFromQueue
    * ?
  * sqluVendorCallWrapper
    * Envoltura de mecanismo externo.
  * sqluVendorTermProcess
    * ?
  * sqluWriteToQueue
    * ?
  * sqluxGetAvailableHeapPages
    * Afinamiento del buffer para backup.
  * sqluxGetDegreeParallelism
    * Afinamiento del buffer para backup.
  * sqluxLogDataStats
    * Cálculo del tamaño del backup.
* DRDA Application Server
  * sqljsTermAgentReply
    * Se mataron las conexiones, sql1224.
* fast comm manager
  * sqkfBufferManager::initBufferManager
    * ?
  * sqkfChannelManager::initChannelManager
    * ?
  * sqkfDynamicResourceMgr::AdjustResources
    * ?
  * sqkfNodeManager::initNodeManager
    * ?
  * sqkfSessionManager::initSessionManager
    * ?
  * sqlkf_init_allocate_shared
    * ?
* Health Monitor
  * db2HmonEvalReorg
    * Chequeo de health monitor para reorganización
  * HealthIndicator::update
    * Actualización de estado del Health Center.
* oper system services
  * DB2VEND_main
    * ?
  * sqloInvokeVendorFunction
    * Reiniciando mecanismo fenced.
  * sqloKAAnalyze
    * ?
  * sqloReadVendorRC
    * Reiniciando mecanismo fenced.
  * SqloOSEnvConfig::logChangesAndErrors
    * ?
  * sqloReadVendorRC
    * ?
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
  * SQLP_PR_ASYNC_FLUSH_TABLE::initialize
    * ?
  * sqlpAllocatePRCB
    * ?
  * sqlpgSwitchCopyPongToPing
    * ?
  * sqlplfrDoScanNext
    * ?
  * sqlplfrFMReadLog
    * Se encontró cadena de logs más reciente. Después de un backup.
  * sqlplfrScanNext
    * ?
  * sqlplfrVerifyLogPages
    * ?
  * sqlpPRecReadLog
    * ?
  * sqlprDbBackwardPhase
    * ?
  * sqlprecm
    * ?
  * sqlpRecoveryPhasePostProcessing
    * ?
  * sqlpresr
    * ?
  * sqlprudm
    * ?
  * sqlprReportRedoEndProcessingStatus
    * ?
  * sqlpshrEdu
    * ?
  * sqlpshrScanOpen
    * ?
  * sqlpshrSetStartLsoFromLsnOrLfsLsn
    * ?
* relation data serv
  * sqlr_init_tstat
    * Analiza los valores actuales de ciertos parámetros.
  * sqlrr_appl_init
    * ?
  * sqlrr_array_input
    * ?
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
  * stmmAttachToShmAtStartup
    * ?
  * stmmCalcAutoScaleFactor
    * Los valores de memoria solicitada exceden la memoria física.
  * stmmLog
    * Borrado del archivo de log del STMM.
  * stmmLogGetFileStats
    * Creación de un archivo para los logs de STMM.
* SQO Memory Management
  * sqloMemLogPoolConditions
    * ?
* trace services
  * sqlt_logerr_data (secondary logging func
    * ?
