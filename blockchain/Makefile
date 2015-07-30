CFLAGS = -Wall -ansi -pedantic -Wno-c++11-long-long -Wextra

blockchain.out: *.cpp *.h Makefile
	g++ $(CFLAGS) *.cpp -o blockchain.out
run:	blockchain.out
	./blockchain.out
.PHONY: clean
clean:
	-rm -f blockchain.out
