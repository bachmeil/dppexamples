dprog:
	d++ poly.dpp -of=dpoly --include-path=/usr/include -L/usr/lib/x86_64-linux-gnu/libgsl.so -L/usr/lib/liblapack.so -L/usr/lib/libblas.so

cprog:
	gcc poly.c -o poly -I/usr/include -L/usr/lib/x86_64-linux-gnu -lgsl -llapack -lblas
