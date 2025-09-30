# Number Theory: Addition

In this lab you've learned the basics of number theory as it relates to addition.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

Summary:

In this lab we first started with the light switch on the stair way . When both the switches we on (1) or when both were off (0) the light were supposed to be off (ouput = 0). So this logic of the stair way represents XOR logic in the light.v and we used the same logic in adder.v but we also added the Carry functionality for if the one bit addition goes over one bit. We then used this XOR logic (of the adder) for two bit addition including the functionality of a carryout. When we went over two bits (# output sum bits > # input bits), the most significant bit was represented by the carryout.


## Lab Questions

### 1 - How might you add more than two bits together?

To add more than two bits together you would use another full adder for additional radix.

### 2 - What is the importance of the XOR gate in an adder? 

The importance of the XOR gate is so that the output values of the sum part of the additon matches the truth table. The XOR covers the "sum" and the "carry out" utilizes an AND gate.

### 3 - What is the largest number a two bit adder can handle? What happens when you go over?

The largest number a two bit adder can handle is adding 11 and 11 which gives us 110 (3+3=6). If you go over the maximum input size of two bits, any radix more significant than the first two (A_0 and A_1) of the input would not be accounted for because there are only two adders in the two bit adder.


