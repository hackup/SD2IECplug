PROJECT=SD2IECplug
all: $(PROJECT).zip

rename:
	@if [ -f $(PROJECT)-Edge?Cuts.gm1 ]; then mv $(PROJECT)-Edge?Cuts.gm1 $(PROJECT).gko; fi

$(PROJECT).zip: rename
	zip $(PROJECT).zip $(PROJECT)*.gt? $(PROJECT)*.gb? $(PROJECT)*.drl $(PROJECT)*.gko

clean:
	rm -f $(PROJECT).zip
