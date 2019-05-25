#
#the tab has been transferred to 4 space in ~/.vimrc
#So the make would report error. the resolution is ; set ts=4 set noexpandtab %retab!  
#
ab: ab.o
	cc -o ab ab.o
ab.o:ab.c
	cc -c ab.c
clean:
	rm *.o ab
	
