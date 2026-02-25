CXX = g++
CXXFLAGS = -Wall -Wextra -Werror -pedantic -std=c++17 #-pthread

TARGET = myprogram
SRCS = main.cpp

.PHONY: all clean run

all: $(TARGET)

$(TARGET): $(SRCS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRCS)

run: $(TARGET)
	./$(TARGET)

clean:
	rm -f $(TARGET)