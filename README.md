# Binary Adder

This is a digital circuit that implements the functionality of a 2-bit binary adder using basic digital logic gates. It can add two 2-bit binary numbers and produce a 3-bit output (including the carry-out bit).

* The circuit consist of two half adders and one OR gate to handle the carry bits.
* The circuit consist of two Half Adders connected to form a full adder for the Least Significant Bits (LSB) and Most Significant Bits (MSB).
* The first half adder will add the least significant bits (A0 and B0).
* The second half adder will add the most significant bits (A1 and B1), along with the carry from the first half adder.
* The OR gate will combine the carry outputs from the two half adders to produce the final carry-out.

[Click here](https://www.youtube.com/watch?v=1evKw690mVY) to visit YouTube for a simulation video of the circuit to verify it works as intended and produces correct outputs.<br>
There is also a detailed Report of the design process which includes theoretical expectations of the circuit outputs across different inputs. [Click here](https://github.com/calebmohapi/CS3520/blob/main/Report.docx) to view it.

