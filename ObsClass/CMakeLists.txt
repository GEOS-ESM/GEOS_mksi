
set (ObsClass_files
    obsys-nas-gaas.rc
    obsys-nas-merra2.rc
    obsys-nas.rc
    obsys-nccs-arc.rc
    obsys-nccs-gaas-geosit.rc
    obsys-nccs-gaas-r21c.rc
    obsys-nccs-gaas.rc
    obsys-nccs-geosit.rc
    obsys-nccs-merra2.rc
    obsys-nccs-r21c.rc
    obsys-nccs.rc
    obsys-ncep.rc
   )
install(
   FILES ${ObsClass_files}
   DESTINATION etc
   )

