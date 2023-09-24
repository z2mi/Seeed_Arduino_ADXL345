cmake_minimum_required(VERSION 3.5)
set ( ADXL345_SRCS
      "ADXL345.cpp"
) 
idf_component_register(SRCS ${ADXL345_SRCS}
                    INCLUDE_DIRS "."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(ADXL345)