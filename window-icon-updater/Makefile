all:
	@true

install:
	install -D icon-receiver $(DESTDIR)/usr/lib/qubes/icon-receiver
	install -D qubes.WindowIconUpdater $(DESTDIR)/etc/qubes-rpc
	install -m 0664 -D qubes.WindowIconUpdater.policy $(DESTDIR)/etc/qubes-rpc/policy/qubes.WindowIconUpdater
