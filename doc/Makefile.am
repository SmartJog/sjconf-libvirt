man8_MANS = sjconf-libvirt.man

CLEANFILES = $(dist_man8_MANS)
EXTRA_DIST = $(wildcard $(srcdir)/*.t2t)

SUFFIXES = .t2t

.t2t.man:
	$(TXT2TAGS) -o $@ $<
