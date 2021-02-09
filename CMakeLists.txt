idf_component_register(INCLUDE_DIRS include)

target_compile_definitions(${COMPONENT_TARGET} INTERFACE HAS_UNCAUGHT_EXCEPTIONS=1)
