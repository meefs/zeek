zeek_add_plugin(
    Zeek UDP
    SOURCES UDP.cc UDPSessionAdapter.cc Plugin.cc
    BIFS events.bif)
