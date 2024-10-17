# Makefile
all: install

install:
	install -Dm755 bin/image-optimizer "$(DESTDIR)/usr/bin/image-optimizer"
	install -Dm644 LICENSE "$(DESTDIR)/usr/share/licenses/image-optimizer/LICENSE"
	install -Dm644 README.md "$(DESTDIR)/usr/share/doc/image-optimizer/README.md"

uninstall:
	rm -f "$(DESTDIR)/usr/bin/image-optimizer"
	rm -rf "$(DESTDIR)/usr/share/licenses/image-optimizer"
	rm -rf "$(DESTDIR)/usr/share/doc/image-optimizer"

.PHONY: all install uninstall
