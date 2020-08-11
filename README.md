# PCB_Design
 A PCB design for a 4-bit multiplier.
 ## 7 segment pcb:
 ![pcb_multiplier](https://github.com/menna15/4-bit-multipler-pcb-design/blob/1d48b894873c6d6d2f1836e227f074a3f42ec5e2/PCB/pcb_multipler.jpg)
 ## Mechanism:
 - the user enters the two numbers - 3 and 4 bits- using dip switches in their 2's complement form.
 - the two numbers are multiplied in the -multiplier- unit.
 - the product is divided into two parts: integer and decimal.
 - the integer part goes to the -int to BCD- unit, the same for the decimal part goes for the -decimal to BCD- unit
 - after being converted into BCD the two parts are represented on three 7-segments.
 - there is sign flag besides the 7-segments
 
 **this project is served as a partial fulfillment of the Requirements for CMP1010 -logic design- for the first-year computer engineering department 2019-2020 {Cairo university, faculty of engineering}**
