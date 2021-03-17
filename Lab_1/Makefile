buildMain: task.c
	gcc -o task task.c -lm

buildTest: task.c task_test.c
	gcc -o task_test.exe task.c task_test.c -Dmain=_main -lm

#.PHONY: clean
#clean:
#	del *.exe
	
