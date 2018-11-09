# Linux-scripts -intmon -  Interrupt monitoring Script 

 With many 20s or 30s of CPUs and it is hard to track which interface or device is causing the Interrups on a heavily loaded system.
 This handy tool will help to give a summary
 
 ./intmon

HELP
---------
This Program will print rate of Interrupts per device



Usage :  ./intmon -i [--interval] -t [--threshold]


   Interval: Interval to print output
   Threshold : Print only if rate is above this value



./intmon  -i 1 -t 10


         Date/Time               Cpu     Device          Inerrupts/ 1 second
2018-11-09 11:33:34.913617       CPU3    timer  interrupts               24
2018-11-09 11:33:34.913747       CPU2    ens192-rxtx-0           14
2018-11-09 11:33:34.913854       CPU2    ens160-rxtx-0           15


         Date/Time               Cpu     Device          Inerrupts/ 1 second
2018-11-09 11:33:35.917240       CPU3    timer  interrupts               18
2018-11-09 11:33:35.917385       CPU2    ens192-rxtx-0           12
2018-11-09 11:33:35.917556       CPU2    ens160-rxtx-0           14


         Date/Time               Cpu     Device          Inerrupts/ 1 second
2018-11-09 11:33:36.921534       CPU3    timer  interrupts               22
2018-11-09 11:33:36.921687       CPU2    ens192-rxtx-0           11
2018-11-09 11:33:36.921759       CPU2    ens160-rxtx-0           13

'
