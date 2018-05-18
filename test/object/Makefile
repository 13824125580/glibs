INCLUDE=-I/home/czl/Workspace/glib/libs/include \
	-I/home/czl/Workspace/glib/libs/lib/glib-2.0/include \
	-I/home/czl/Workspace/glib/libs/include/glib-2.0 

LIBS=-L/home/czl/Workspace/glib/libs/lib/ -lgobject-2.0 -lglib-2.0
CC = gcc
all:
	$(CC) -c boy.c ${INCLUDE}
	$(CC) -c man.c ${INCLUDE}
	$(CC) -c main.c ${INCLUDE}
	$(CC) -o simple main.o boy.o man.o  ${LIBS}
clean:
	-rm -fr *.o simple
