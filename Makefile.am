AUTOMAKE_OPTIONS = gnu

SUBDIRS = po

install-exec-local:
	$(mkinstalldirs) $(DESTDIR)/$(bindir)
	$(INSTALL_PROGRAM) bin/main $(DESTDIR)/$(bindir)/$(PACKAGE_NAME)

uninstall-local:
	rm -f $(DESTDIR)/$(bindir)/$(PACKAGE_NAME)

clean:
	rm -f bin/main
