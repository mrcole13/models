#=============================================================================
# File: Makefile
#
# Warnings:
#   !!! THIS IS AN AUTO-GENERATED FILE. PLEASE DO NOT EDIT. !!!
#=============================================================================

.POSIX:
.SCCS_GET:

# Displays the available targets in tabular format.
help :
    @echo "============================================================"
    @echo " Primary Targets       | Compile     Link"
    @echo "============================================================"
    @echo "   all                 |   YES        YES"
    @echo "   comp_src            |   YES         NO"
    @echo "   link_sys            |   YES        YES"
    @echo "   clean               |   "
    @echo "============================================================="

include C:/Users/rrice/410workspace/jp_character_test_ascii/gen/code_generation/Makefile.in
include C:/Users/rrice/410workspace/jp_character_test_ascii/gen/code_generation/Makefile.user

# use Target C Cross Compiler
CMD_TARGET_COMPILE    = ${CMD_COMPILE}
CMD_TARGET_ASSEMBLE   =
CMD_TARGET_PREPROCESS =
CMD_TARGET_LINK       = ${CMD_LINK}

# Relative paths for object and source files.
SRC_PATH=
OBJ_PATH=
#=============================================================================
# List of all object files to be compiled.
#=============================================================================
USER_OBJ_TARGETS = \
	${OBJ_PATH}jp_character_test_ascii_sys_main.o \
	${OBJ_PATH}System.o \
	${OBJ_PATH}System_class1_class.o \
	${OBJ_PATH}sys_user_co.o \
	${OBJ_PATH}sys_xtuml.o \

#=============================================================================
# Source file target recipes.
#=============================================================================
${OBJ_PATH}jp_character_test_ascii_sys_main.o : ${SRC_PATH}jp_character_test_ascii_sys_main.c
	${CMD_TARGET_COMPILE}
	${CMD_TARGET_ASSEMBLE}

${OBJ_PATH}System.o : ${SRC_PATH}System.c
	${CMD_TARGET_COMPILE}
	${CMD_TARGET_ASSEMBLE}

${OBJ_PATH}System_class1_class.o : ${SRC_PATH}System_class1_class.c
	${CMD_TARGET_COMPILE}
	${CMD_TARGET_ASSEMBLE}

${OBJ_PATH}sys_user_co.o : ${SRC_PATH}sys_user_co.c
	${CMD_TARGET_COMPILE}
	${CMD_TARGET_ASSEMBLE}

${OBJ_PATH}sys_xtuml.o : ${SRC_PATH}sys_xtuml.c
	${CMD_TARGET_COMPILE}
	${CMD_TARGET_ASSEMBLE}

#=============================================================================
# Build environment targets.
#=============================================================================
# Clean out compiled object files.
clean :
    @'rm' -f ${OBJ_PATH}*.o

# Target for compiling objects.
comp_src : ${USER_OBJ_TARGETS}

# Target for link system.
link_sys : ${USER_OBJ_TARGETS}
    $(CMD_TARGET_LINK) $(USER_OBJ_TARGETS)

all : comp_src link_sys
