include ../config.mk
OBJS = group hostname inittab passwd rc rc.chk skel/.profile

all: $(OBJS)
	$(UCP) $(FSIMG) < install.ucp

