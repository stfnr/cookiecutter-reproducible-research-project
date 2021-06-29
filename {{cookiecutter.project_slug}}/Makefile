.PHONY: all data processing quantification statistics figures

HOSTNAME := $(shell hostname)

include Makefile.config

$(info ** Running on host $(HOSTNAME) !**)
 
data:
	$(info ** make data **)
	eval $(python_cmd) < src/data/01_data.py > ./logs/01_data.log

processing:
	$(info ** make processing **)
	eval $(matlab_cmd) < src/data/02_processing.m  > ./logs/02_processing.log

quantification:
	$(info ** make quantification **)
	eval $(matlab_cmd) < src/data/03_quantification.m > ./logs/03_quantification.log

statistics:
	$(info ** make statistics **)
	eval $(matlab_cmd) < src/data/04_statistics.m  > ./logs/04_statistics.log

figures:
	$(info ** make figures **)
	eval $(matlab_cmd) < src/data/05_figures.m  > ./logs/05_figures.log

all: data processing quantification statistics figures
