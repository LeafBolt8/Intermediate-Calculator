Topics Covered:
- Basic IO
- Arithmetic Operators
- Assignment Operators
- For Loops
- If else
- Increment and Decrement
- While loop
- Break and Continue

Key Points: (Or rather, how do I loop or jump things?)
- while (true OR a variable assigned as true (to be able to be modified)) { break; (assuming its inside the bracket while dominates) } = stops/jumps to a higher hierarchy outside the bracket.
- while { continue (assuming its inside the bracket while dominates) }= loops the program inside the bracket.
- Note that break and continue are always in the if, else if, else when a selection to loop/stop is made from user input.

Break vs. repeat = false:
- Break will take you elsewhere.
- Meanwhile setting the while to false will take you back, giving you a chance to try again after a wrong input.
- E.g. when you have wrong input, break will take you away from to calc and send u to the main menum while = false will stay in the user question.

Structure of each calculator:
1. If calcu is selected code (selection == user input)
2. Welcome text
3. Declare a bool variable as true
4. Then use that variable for while (variable name)
5. Include the WHOLE calcu code inside while's brackets
6. Use either continue; (to loop the calcu) break; (for main menu) or (while variable name) = false (for wrong input) ALL OF THESE INSIDE IF ELSE THAT ASKS OPTIONS ON WHAT THEY WANNA DO AFTER USING THE CALCU.
7. Closing the if and while brackets.
