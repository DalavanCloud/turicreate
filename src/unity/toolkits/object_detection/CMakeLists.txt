project(unity_toolkits)

make_library(unity_object_detection
  SOURCES
    class_registrations.cpp
    object_detector.cpp
    od_data_iterator.cpp
    od_yolo.cpp
  REQUIRES
    image_io
    random
    table_printer
    unity_core
    unity_neural_net
)
