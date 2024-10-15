
zephyr_library()
zephyr_library_sources_ifdef(CONFIG_ENABLE_DUMMY dummy.c)
zephyr_include_directories_ifdef(CONFIG_ENABLE_DUMMY .)

