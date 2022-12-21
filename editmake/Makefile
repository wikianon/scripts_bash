#######################################################################################################
#                                                                                                    
# Autor: Jean Zonta                                                                                  
# Pseudonym: wiki.anon                                                                               
# Script Name: Makefile based on java makefile                                                       
# License: GNU/GPL V3                                                                                
# DateTime: sex 16 mar 2018 22:41:10
# echo "}oqo4gtutF_gnuu4ius4hx" | perl -pe \ 's/(.)/chr(ord($1)-2*3)/ge'                             
# echo 'comhttps://slackwarewww' | sed 's@\(com\)\(https://\)\(slackware\)\(www\)@\2\4.\3.\1 ..!!!@' 
#                                                                                                    
#######################################################################################################
SUB=%
OBJ=*.o
EOBJ=%.o

CXX=g++
SRC=*.c*
ESRC=%.c*

NAME=date
EBIN=%$(NAME)
BIN=$(NAME)

all: $(NAME)

$(EOBJ):$(ESRC)

	$(CXX) -c $(SRC)

$(EBIN):$(EOBJ)

	$(CXX) -o $(BIN) $(OBJ)

$(SUB):$(EBIN)

	./$(BIN)
	rm -rf $* $(OBJ)