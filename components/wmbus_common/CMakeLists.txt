idf_component_register(
    SRCS 
        "address.cc"
        "aes.cc"
        "aescmac.cc"
        "dvparser.cc"
        "formula.cc"
        "manufacturer_specificities.cc"
        "meters.cc"
        "translatebits.cc"
        "units.cc"
        "util.cc"
        "wmbus.cc"
        "wmbus_utils.cc"
    INCLUDE_DIRS "."
    REQUIRES esphome_core
)
