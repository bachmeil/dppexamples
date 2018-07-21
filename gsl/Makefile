poly-d:
	d++ poly.dpp -of=dpoly --include-path=/usr/include -L/usr/lib/x86_64-linux-gnu/libgsl.so -L/usr/lib/x86_64-linux-gnu/liblapack.so -L/usr/lib/x86_64-linux-gnu/libblas.so

poly-c:
	gcc poly.c -o poly -I/usr/include -L/usr/lib/x86_64-linux-gnu -lgsl -llapack -lblas

root-d:
	d++ root.dpp -of=droot --include-path=/usr/include -L/usr/lib/x86_64-linux-gnu/libgsl.so -L/usr/lib/x86_64-linux-gnu/liblapack.so -L/usr/lib/x86_64-linux-gnu/libblas.so

root-c:
	gcc root.c -o root -I/usr/include -L/usr/lib/x86_64-linux-gnu -lgsl -llapack -lblas

