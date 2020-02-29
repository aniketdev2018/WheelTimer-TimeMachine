# WheelTimer-TimeMahine
#Author aniket kumar


Steps for executing the project -
step1: open your windows command prompt 
step2: locate or reach that location whereever your WheelTimer project is suppose your project is on desktop type : cd desktop
step3: type:  ls  to see all file 
step4: now run  cat Readme 
step5: compile all gcc containing file  ie. copy all gcc conatining file and paste after succesfull compile of all programm 
step6: now execute  .\exe   

compile the program as :

gcc -g -c LinkedListApi.c -o LinkedListApi.o
gcc -g -c WheelTimer.c -o WheelTimer.o
gcc -g -c main.c -o main.o
gcc -g main.o WheelTimer.o LinkedListApi.o -o exe -lpthread

# now run the executable as .\exe


Thanks 
