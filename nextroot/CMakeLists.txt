PROJECT(TxemaOS-nextroot)

MESSAGE(STATUS "Creating NextRoot directory")
INSTALL(DIRECTORY ../grub DESTINATION boot)
INSTALL(DIRECTORY ../include DESTINATION .)
