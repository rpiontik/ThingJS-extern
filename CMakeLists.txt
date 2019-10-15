# Project body
message(">>>>>>>>>>>>>>> ThingJS extern included <<<<<<<<<<<<<<<<<<<")

idf_component_register(
        SRC_DIRS "./mJS" "./mongoose"
        INCLUDE_DIRS  "./mJS" "./mongoose"
)