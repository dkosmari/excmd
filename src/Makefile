CXX := g++ -std=c++20

CXXFLAGS := -Wall -Wextra -Werror


.PHONY: all clean


all: example

clean:
	$(RM) example


example: example.o
	$(CXX) $(CXXFLAGS) $^ -o $@ $(LDFLAGS) $(LIBS)

