# syntax-flow-game
Try to keep the flow going without causing a syntax error. The syntax gets harder and the speed gets faster the longer you go.

Planning to build this as a ios and android app.

Basic idea:
Its sort of like tetris...
You are given an 'n' (1<n<6 depending on difficulty) number of options.
Each option is a simple code block. As simple as a single character ('{', ';', '(') or as complex as ('/n this()', '/n const newFunct = (param) => {').
You have a short amount of time to pick your option. 
When you pick your option it will be placed at the end of your code block (at the beginning the code block will be blank)
and then the code block will be quickly checked for syntax errors.
score will be based on how many option choices you get through with multipliers for choosing more complex options ('/n this()' worth more points than ';' for example).
