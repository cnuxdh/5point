

INCLUDE_DIRECTORIES(/usr/local/include  
										../
										../matrix
										../imagelib
										)


ADD_LIBRARY(5point
	5point.c
	poly1.c
	poly3.c
	)