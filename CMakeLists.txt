#idf_component_register(SRCS "rotary_encoder.c" INCLUDE_DIRS include)

set(COMPONENT_ADD_INCLUDEDIRS include)
set(COMPONENT_SRCS "rotary_encoder.c")
idf_component_register(SRCS ${COMPONENT_SRCS} 
                       REQUIRES driver 
                       INCLUDE_DIRS ${COMPONENT_ADD_INCLUDEDIRS})
