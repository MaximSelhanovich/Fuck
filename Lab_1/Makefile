buildMain: task.c
	gcc -o task task.c -lm
	./task

buildTest: task.c task_test.c
	gcc -o task_test task.c task_test.c -Dmain=_main -lm

runTest:
	./task_test

.PHONY: clean
clean:
	del *.exe
	
