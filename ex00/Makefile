# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: cyrmorin <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2016/09/12 15:33:38 by cyrmorin          #+#    #+#              #
#    Updated: 2016/09/12 17:32:38 by cyrmorin         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRCS = srcs/ft_putchar.c srcs/ft_strlen.c srcs/ft_strcmp.c srcs/ft_putstr.c srcs/ft_swap.c

all: $(NAME)

$(NAME):
	gcc -c $(SRCS) -I includes
	ar rc $(NAME) *.o
clean:
	rm -f *.o

fclean: clean
	rm -f $(NAME)

re: fclean all
