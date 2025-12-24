The single assembly file supports all of the below mentioned devices using conditional assembly.  In the MPLAB IDE just select the any one of the device listed below and build. This will produce HEX file, List file for the selected device. We can add more devices if we are in need.  
FM tuner using RDA Microelectronics RDA5807 tuner with NEC IR Remote control  using  
* PIC10F200  
* PIC10F202  
* PIC10F204  
* PIC10F206  
* PIC10F220 
* PIC10F222   
* PIC12F508  
* PIC12F509   
* PIC12F510  

MPLAB IDE **8.92**  
MPASM **5.51**   

**PIC10F2XX PIN ASSIGNMENT**

* SDA<->GP2  
* SCL<->GP1  
* IRx<->GP3   

**PIC10F5XX PIN ASSIGNMENT** 
 
* IRx        EQU    GP3  
* SCL        EQU    GP4  
* SDA        EQU    GP5  
