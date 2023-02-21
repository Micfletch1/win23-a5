objects = main.o addition.o subtraction.o division.o multiplication.o

calculator: $(objects)
	cc -o calculator $(objects)
$(objects): %.o:%.c operations.h
	cc -c $< -o $@
clean:
	rm -f $(objects)

