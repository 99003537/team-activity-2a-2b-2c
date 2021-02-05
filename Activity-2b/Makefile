all: run clean 
#all provides sequence of command

BUILD = build


SRC = main.c\
src/christyjohnson.c\
src/dhyan.c\
src/harshita.c\
src/lakshita.c\
src/namratha.c\
src/Rishita.c\
src/satya.c\
src/srushti.c\
src/sumit.c\


#

$(BUILD):
	mkdir build


INC = -Iheader 


PROJECT_NAME= nameprint.out


$(PROJECT_NAME): $(SRC)
	gcc $(SRC) $(INC) -o $(PROJECT_NAME)


run: $(PROJECT_NAME)
	./$(PROJECT_NAME)
	
clean:
	rm -rf $(PROJECT_NAME) documentation/html
