.PHONY: install

install:
	@[ ! -f ~/bin/play ] || (echo "play already in ~/bin" && exit 1)
	@[ -d ~/bin ] || mkdir -p ~/bin
	@ln -s $(shell pwd)/play ~/bin/play
	@echo "Install successful"

uninstall:
	@[ -f ~/bin/play ] || (echo "play is not installed in ~/bin" && exit 1)
	@rm ~/bin/play && echo "Uninstall successful"
