esma_add_subdirectories (
  @MAPL
  )

Special case - GFDL_fms can be built with variant precisions.
add_subdirectory (@GFDL_fms GFDL_fms_r4)

if (FV_PRECISION STREQUAL "R4")
  add_subdirectory (@GFDL_fms GFDL_fms_r4)
else ()
  add_subdirectory (@GFDL_fms GFDL_fms_r8)
endif ()  
