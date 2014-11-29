#/usr/bin/make
SRC = $(DESTDIR)/usr/src
SHARE = $(DESTDIR)/usr/share/$(NAME)-dkms

all:

clean:

install:
	mkdir -p "$(SRC)/$(NAME)-$(VERSION)"
	
	cp -a \
		"dkms.conf"	\
		../*.[ch]	\
		../*.in		\
		../README*	\
		../irq*		\
		../configure	\
		../*.sh		\
			"$(SRC)/$(NAME)-$(VERSION)"/
	
	chmod 644 -R "$(SRC)/$(NAME)-$(VERSION)"
	chmod 755    "$(SRC)/$(NAME)-$(VERSION)"

