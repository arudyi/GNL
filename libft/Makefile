#******************************************************************************#
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: arudyi <arudyi@student.unit.ua>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/10/27 13:08:54 by arudyi            #+#    #+#              #
#    Updated: 2018/11/04 17:22:29 by arudyi           ###   ########.fr        #
#                                                                              #
#******************************************************************************#

NAME = libft.a
OBJECTS = *.o
FILES =  *.c
FLAGS  = -Wall -Werror -Wextra
HEADER = includes

all: $(NAME)

$(NAME):
	gcc $(FLAGS) -c $(FILES) -I $(HEADER)
	ar -rc $(NAME) $(OBJECTS)

clean:
	rm -f $(OBJECTS)
	
fclean: clean
	rm -f $(NAME)

re:	fclean all
