#################################################
# Latex-Makefile
# Created at 05.09.2011
# Author: Thomas Hamböck
#################################################

SOURCE=WirelessSensorNetworks

all: standard

standard:
	rubber -d $(SOURCE)

clean:
	rubber -d --clean $(SOURCE)

view: clean all
	evince $(SOURCE).pdf

