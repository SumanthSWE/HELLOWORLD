# comments
# Target : dependency
#<TAB>Command

PROJECT_NAME = all.exe
SRC = test.c\
src\sum.c\
src\sqr.c

INC = inc

$(PROJECT_NAME): $(SRC)
	gcc $(SRC) -I $(INC) -o all.exe

run: $(PROJECT_NAME)
	$(PROJECT_NAME)

clean: 
	del /q *.exe