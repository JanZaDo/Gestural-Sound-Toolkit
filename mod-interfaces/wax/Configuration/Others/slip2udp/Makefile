# Makefile

CC 		:= gcc 
CFLAGS	:= -isysroot /Developer/SDKs/MacOSX10.5.sdk \
	-mmacosx-version-min=10.5

all: build

build: Makefile slip2udp-noDump.c
	$(CC) $(CFLAGS) -o slip2udp-noDump slip2udp-noDump.c

clean:
	rm -f slip2udp-noDump.o core
