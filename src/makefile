CC = g++
DEBUG = -O3 #-D_GLIBCXX_USE_CXX11_ABI=0
CFLAGS = -std=c++11 $(DEBUG) -c
LFLAGS = -std=c++11 $(DEBUG)

RM = rm -f  			# rm command
TARGET = FAHES
SRCS = $(shell ls *.cpp)
OBJS = $(SRCS:.cpp=.o)

all: ${TARGET}

$(TARGET): $(OBJS)
	$(CC) ${LFLAGS} $(OBJS) -o ${TARGET}



clean:
	-${RM} ${TARGET} ${OBJS} 
rmo:
	-${RM} ${OBJS} 
