### THIS IS A TRAVIS MAKEFILE DON'T USE IT NORMALLY

OBJ = test_main.o

%.o: %.cpp 
	$(COMPILER) -c -o $@ $< $(CPPVERFLAG) $(EXTRAARGS) $(CMDARGS)

xxhashmake: $(OBJ)
	$(COMPILER) -o $(OUTNAME) $^ -I. -Wall -Wextra $(CPPVERFLAG) $(EXTRAARGS) $(CMDARGS) $(LIBS)