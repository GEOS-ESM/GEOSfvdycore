esma_add_subdirectories (
  MAPL
  GMAO_Shared
  )

if (FV_PRECISION STREQUAL R4)
  esma_add_subdirectory (FMS RENAME fms_r4)
elseif (FV_PRECISION STREQUAL R8)
  esma_add_subdirectory (FMS RENAME fms_r8)
elseif (FV_PRECISION STREQUAL R4R8)
  esma_add_subdirectory (FMS RENAME fms_r4)
  esma_add_subdirectory (FMS RENAME fms_r8)
endif ()
