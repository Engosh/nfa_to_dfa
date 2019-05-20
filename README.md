# nfa_to_dfa

This rogram converts NFA to DFA using powerset method

///////////////////////////////////////////////////////////////////////////////////////////////////////////////

INPUT:
The program prompts the user to input 
1.The number of states in the NFA
2.The start state
3.The number of final states
4.The final states
5.The number of input symbols
6.The respective input symbols

It then asks the user to input the transition as move(a,b) 	a - current state
								b - current input symbol

the prompt goes to move(a,b+1) on the input of -1
///////////////////////////////////////////////////////////////////////////////////////////////////////////////

OUTPUT:

Once the user gives all the input the Output is displayed as DFA transition table with the states reassigned names starting from 'A', the sates in NFA which constitute it and then the transitions for each input.
