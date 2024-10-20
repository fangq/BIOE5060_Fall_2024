for:
	# add commands below to build forloop.c
while:
	# add commands to build whileloop.c
for.txt: for
	./forloop > for.txt
while.txt: while
	./whileloop > while.txt
test: for.txt while.txt
	diff for.txt while.txt > diff.txt
	[ -s diff.txt ] && false || true
