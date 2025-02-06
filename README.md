# Binary Addition
Despite being a base 2 system, the binary addition operation functions similarly to the base 10 decimal system. There are just two numbers in the binary system: 1 and 0. The binary number system is used for the majority of computer system functions. To switch on or off certain operations, the binary code employs the numbers 1 and 0. By converting to base 2, the addition procedure is quite familiar to the decimal system.   
# Rules of Binary Addition
If you keep in mind the following tips or guidelines, binary addition is far simpler than decimal addition. Any binary number may be added with ease by following these guidelines. The following are the four binary addition rules:

0 + 0 = 0 + 1 = 1.

1 + 0 =  1 + 1 =  10.

# Half Adder Circuit
The half adder is a fundamental component of complex adder circuits, including multiple-bit and complete adders. Two single-bit inputs, A and B, are binary added, and two outputs, SUM and CARRY, are produced. 
A digital logic circuit known as a half adder is used to add two single-bit binary values. It has two outputs (SUM and CARRY) and two inputs (A and B). Whether there was a carry-over from the addition of the two inputs is shown by the CARRY output, which is the most important bit of the result, and the SUM output, which is the least significant bit. Basic gates like AND and XOR gates may be used to create the half adder.

The half adder  in the diagram accepts two inputs, A and B, which are the two binary digits that need to be added. The digit to carry to the next place value is Cout, and the sum is output through S. Two logic gates—an AND gate and an XOR gate—make up the actual half adder. The while gate establishes the carry value, while the XOR gate manages the total.
![image](https://github.com/user-attachments/assets/403ab0e5-54f6-45a7-b08b-e52371aab709)

# Truthtable
In the truth table below, we can see every potential output that a half adder may have because it is constructed of logic gates and has a finite number of inputs. This allows us to validate several solutions. For instance, 1 + 1 will provide a Sum of 0 with a Carry of 1, while 0 + 0 will equal 0.

![image](https://github.com/user-attachments/assets/7a9c6155-d077-45ec-bf98-46916aaa83eb)

# How is a complete Half Adder circuit?
Now, with all the information above, we can ceate a complete Half Adder circuit.
![image](https://github.com/user-attachments/assets/70da8d5e-2c6b-4870-b3be-167b39572b0d)

# Physical Half Adder Circuit
Once we understand all the information we need to know we can make the Half Adder circuit in a real circuit using some resistors, some butttons, some wires, some gates and some LED lights.

# References
Admin. (2020, July 28). Binary addition- definition, rules, method, tricks and examples. BYJUS. https://byjus.com/maths/binary-addition/ 
GeeksforGeeks. (2024, September 23). Half adder in digital logic. https://www.geeksforgeeks.org/half-adder-in-digital-logic/ 
