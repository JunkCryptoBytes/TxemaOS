PROJECT(TxemaOS-iso)

MESSAGE(STATUS "Generating ISO script")
FILE(WRITE iso.sh "#!/bin/bash\n grub-mkrescue --compress=xz --product-name=TxemaOS --product-version=0.1.0 -o txemaos.iso next")
INSTALL(PROGRAMS iso.sh DESTINATION ..)
