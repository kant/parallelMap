# parallelMap 1.4.0.9000

- Internal changes only.


# parallelMap 1.4

- Load balancing for multicore, socket and mpi can now be controlled via the flag
  "load.balancing" passed to parallelStart().
  Note that the default for multicore now defaults to disabled load balancing.
- BatchTools mode

# parallelMap 1.3

- parallelGetRegisteredLevels has new argument "flatten"
- parallelShowOptions was converted to parallelGetOptions (with a printer)

# parallelMap 1.2

- Arguments of mcmapply (mc.preschedule, ...) can now be specified via parallelStart
- We import package "parallel" now
- parallelShowRegisteredLevels was changed to parallelGetRegisteredLevels.
  The latter returns a structured object, with a printer method.

# parallelMap 1.1

- Package in general much more stable now
- parallelLibrary was improved a lot
- better / more configurable info messages on console
- BatchJobs mode: working directory for slave jobs is the current working dir on the master,
  not the storage.dir
- BatchJobs mode: errors are thrown, if jobs expire
- parallelMap/Lapply/Sapply: impute.error option
- removed autostart option for stability

## new functions

- parallelSource
- parallelExport

# parallelMap 1.0-83

- First submit to CRAN.

