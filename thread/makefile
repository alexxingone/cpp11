BIN=cpp11_23_wait_for cpp11_22_condVir_proConsu  cpp11_14_async cpp11_20_thread_lambda   
all:$(BIN)

CC=g++
CPPFLAGS=-Wall -std=c++0x  -ggdb
LDFLAGS=-pthread

%.o:%.cpp
	$(CC) $(CPPFLAGS) $(LDFLAGS) -c $<-o $@

.PHONY:
	clean

clean:
	rm   -f *.o $(BIN)
