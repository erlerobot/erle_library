SET (CMAKE_CXX_FLAGS -fpermissive)
SET(Erle_HAL RC_Channel.cpp RCInput.cpp RCInput_PRU.cpp sbus.cpp dsm.cpp GPIO_BBB.cpp RCOutput_PRU.cpp)
add_library(erle SHARED ${Erle_HAL})
TARGET_LINK_LIBRARIES(erle_hal )

