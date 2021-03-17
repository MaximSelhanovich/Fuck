buildMain: task.c
	gcc -o task task.c -lm

buildTest: task.c task_test.c
	gcc -o task_test -Dmain=_main task.c task_test.c -lm

#.PHONY: clean
#clean:
#	del *.exe
	
