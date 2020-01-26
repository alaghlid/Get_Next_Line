# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: alaghlid <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/03/30 14:16:50 by alaghlid          #+#    #+#              #
#    Updated: 2019/03/31 15:38:00 by alaghlid         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME=libft.a
OBJECTS=ft_*.o
SRCS=ft_*.c

all: $(NAME)

$(NAME):
		gcc -Wall -Wextra -Werror -c $(SRCS)
		ar rc $(NAME) $(OBJECTS)
		ranlib $(NAME)

clean:
	    /bin/rm -f $(OBJECTS)

fclean: clean
		/bin/rm -f $(NAME)

re: fclean all
