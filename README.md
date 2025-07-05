# verilog_combinational
Simulation of Combinational Circuits
<details>
 <summary><b>  
Design of full adder </b> </summary>
 #### verilog code
 ```sh
module fulladder(input a,b,cin,
                 output s,cout);
  
  assign s = a^b^cin;
  assign cout = (cin&(a^b))|(a&b); 
  
endmodule
``


</details>



