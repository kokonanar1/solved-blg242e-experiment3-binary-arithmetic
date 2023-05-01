Download Link: https://assignmentchef.com/product/solved-blg242e-experiment3-binary-arithmetic
<br>
In the following experiment, you are going to implement a 16-bit Full adder using the Verilog. In this experiment, you are allowed to use ‘&amp;’ (Bitwise AND), ‘|’ (Bitwise OR), ‘∼’ (Bitwise NOT) operations. Other operations such as ‘ˆ’, ‘+’, ‘-’, ‘*’, ‘/’, ‘<em>&lt;&lt;</em>’,‘{}’ (Concatenate), and ‘<em>&gt;&gt;</em>’ are forbidden. More complex experiments will be later experiments, so you cannot use always, parametric modules, switch case, and if else etc. in this experiment.

<h1>2      Preliminary</h1>

<ul>

 <li>Recall signed and unsigned addition for binary numbers in 2’s complement notation.</li>

 <li>Recall signed and unsigned subtraction for binary numbers in 2’s complement notation.</li>

 <li>Recall what carry, borrow and overflow mean, when they occur and how are they interpreted.</li>

</ul>

<h1>3      Part 1</h1>

In this part, you are requested to implement AND, OR, NOT, XOR modules which you will use in the following parts of the experiment. You are not allowed to use these operators in the following parts, you can only use these modules when you need them.

<h1>4      Part 2</h1>

In this part, you should implement 1-Bit Half Adder module by using AND, OR, NOT, XOR modules which you designed in the first part. Then, you should simulate it for each different combination of input.

1

<em>Experiment 3: Binary Arithmetic</em>

<h1>5      Part 3</h1>

In this part, you should implement 1-Bit Full Adder by using half adder and OR modules which you designed in the previous parts. Then, you should simulate it for each different combination of input.

<h1>6      Part 4</h1>

In this part, you should implement a 4-Bit Full Adder by using 1-Bit Full Adder modules which you designed in the previous part. Then, you should simulate it for ‘7+1’, ‘2+8’, ‘2+3’, ‘14+10’, ‘10+5’, ‘15+4’, ‘6+5’, and ‘8+5’ operations.

<h1>7      Part 5</h1>

In this part, you should implement a 16-Bit Full Adder by using 4-Bit Full Adder module which you designed in the previous part. Then, you should simulate it for ‘29+3’, ‘21+83’, ‘16800+16900’, ‘65534+65100’, ‘202+97’, ‘44+19’, ‘644+255’, and ‘86+572’ operations.

<h1>8      Part 6</h1>

In this part, you should implement a 16-Bit Full Adder-Subtractor by using 16-Bit Full Adder, NOT, XOR, AND, and OR modules which you designed in the previous parts. You should receive an additional input ‘S’ to indicate the numbers are signed or unsigned numbers. If S equals to 0 then the number is unsigned, if S equals to 1 then the number is signed. After that, you should simulate it for ‘29-3, S=0’, ‘21+83, S=0’, ‘16800+16900, S=1’, ‘103-145, S=0’, ‘202+97, S=0’, ‘32400+32200, S=1’, ‘6478-2585, S=0’, and ‘8-52, S=0’ operations.

If there is an overflow or borrow occurs on operation above, then show the these results with flags. Then, show that the operation above is whether valid or not.

<strong>Hint: </strong>You can find slides in the references that can help with overflow, borrow and carry operations.

<h1>9      Part 7</h1>

In this part, you should implement a module which calculates the 3A – 2B by using 16Bit Adder-Subtractor, Adder, NOT, XOR, AND, and OR modules. Then, you should simulate it for ‘A=3105, B=11275’, ‘A=21, B= 83’, ‘A=24, B=32’, ‘A=16386, B=353’, ‘A=202,B=97’, ‘A=44, B=9’, ‘A=64, B=65535’, and ‘A=8, B=52’ inputs.