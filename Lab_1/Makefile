buildMain: task.c
	gcc -o task task.c -lm

buildTest: task.c task_test.c
	gcc -o task_test task.c task_test.c -lm -Dmain=_main

#.PHONY: clean
#clean:
#	del *.exe
	
