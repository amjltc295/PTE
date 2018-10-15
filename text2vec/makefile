CC = g++
CFLAGS = -lm -pthread -Ofast -march=native -Wall -funroll-loops -Wno-unused-result -lgsl -lm -lgslcblas
INCLUDES = -I/usr/local/include -I../Eigen
LIBS = -L/usr/local/lib


infer : infer.cpp
	$(CC) $(CFLAGS) infer.cpp -o infer $(INCLUDES) $(LIBS)

clean :
	rm -rf *.o infer
