all: build 

build: counting

counting: wc.o
	g++ wc.o -o count

wc.o: wc.cc
	 g++ -c wc.cc
	 
	
clean:
	rm -f *.o core *.core
