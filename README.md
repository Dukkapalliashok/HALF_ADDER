# HALF_ADDER
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
# Sum = A XOR B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/020e1531-1c11-42e5-9f27-f09ba459984d)
# Carry = A AND B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/988ae131-0822-4d23-941b-eaafad349a72)
# Verilog code:
module HalfAdder(a,b,sum,carry);

input a,b;

output sum,carry;

xor (sum,a,b);

and (carry,a,b);

endmodule

# output:
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/166902469/7c5a85e5-4254-477c-854b-28b1e04cf7f1)
