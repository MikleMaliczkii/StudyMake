.PHONY: all debug release clean

RELEASE_FLAGS = -O2 -Wall -DNDEBUG
DEBUG_FLAGS = -g -O0 -Wall
RELEASE_EXEC = Kazino-Royal
DEBUG_EXEC = Kazino-Royal-dbg
SOURCE = Kazino-Royal.cpp

all: debug release

debug: Kazino-Royal-dbg

Kazino-Royal-dbg: Kazino-Royal.cpp
g++ $(DEBUG_FLAGS) Kazino-Royal.cpp -o Kazino-Royal-dbg

release: $(RELEASE_EXEC)

Kazino-Royal: Kazino-Royal.cpp
g++ $(RELEASE_FLAGS) Kazino-Royal.cpp -o Kazino-Royal

clean:
rm -f Kazino-Royal Kazino-Royal-dbg
