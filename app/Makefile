# name of your application
APPLICATION = mls160a

# If no BOARD is found in the environment, use this default:
BOARD ?= ssv-mls160a

# Build with riotboot
FEATURES_REQUIRED += riotboot
USEMODULE += riotboot_flashwrite

# This has to be the absolute path to the RIOT base directory:
RIOTBASE ?= $(CURDIR)/../RIOT

USEMODULE += bmi160
USEMODULE += tsrb
USEMODULE += hashes

# Comment this out to disable code in RIOT that does safety checking
# which is not needed in a production environment but helps in the
# development process:
DEVELHELP ?= 1

# Change this to 0 show compiler invocation lines by default:
QUIET ?= 1

include $(RIOTBASE)/Makefile.include
