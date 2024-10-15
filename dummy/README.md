## An exemplary Zephyr external module

An exemplary dummy Zephyr module with snippets that can be pulled by an application by:

```
# 'dummy' location
set(DUMMY_PATH ${CMAKE_CURRENT_SOURCE_DIR}/../dummy)
list(APPEND EXTRA_ZEPHYR_MODULES ${DUMMY_PATH})
...
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
```
