CC = gcc
CFLAGS = -g -Wall

#LDFLAGS = -lgpiod

nuvoicp: main.o icp.o stub.o
	$(CC) $(CFLAGS) -o nuvoicp $^ $(LDFLAGS)
clean:
	rm -f nuvoicp *.o
