##
## Makefile for  in
##
## Made by Jean PLANCHER
## Login   <planch_j@epitech.net>
##
## Started on  Thu Apr 28 06:00:21 2016 Jean PLANCHER
## Last update Thu Apr 28 06:14:57 2016 Jean PLANCHER
##

MV	= mv

RM	= rm -f

NAME	= pepito

all:
	make -C ../exploit
	$(MV) ../exploit/pepito ./

secret:
	gcc -shared -Wl,-soname -fPIC -c src_lib/libsecret.c -I../sources/includes

supersecret:
	@echo "k"

debug:
	@echo "kesako"

clean:
	make clean -C ../exploit

fclean: clean
	$(RM) $(NAME)

re: fclean all
