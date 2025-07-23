Aim : To study and implement Operators in C++

Software Used : VS Code


This experiment is divided into two parts:

A. Operator Demonstration

In this part, we explore the three core categories of operators in C++:

Arithmetic Operators: Used for basic mathematical operations such as:

Addition (+)

Subtraction (-)

Multiplication (*)

Division (/)

Modulus (%)

Relational Operators: Used to compare two values and return a boolean result (true or false). These include:

Equal to (==)

Not equal to (!=)

Greater than (>)

Less than (<)

Greater than or equal to (>=)

Less than or equal to (<=)

Logical Operators: Used to combine relational expressions and return logical outcomes:

Logical AND (&&)

Logical OR (||)

Logical NOT (!)

This section of the program helps understand how operators work and interact in real-time computations and decision-making.

B. Conditional Logic and Coordinate Plane
The second part focuses on conditional decision-making using if-else statements. 
It takes two float values (x and y) representing coordinates on a 2D plane and determines:

If the point lies at the origin (0,0)

If it lies on the X-axis or Y-axis

If not on axes, then which quadrant it belongs to:

Quadrant I: x > 0 && y > 0

Quadrant II: x < 0 && y > 0

Quadrant III: x < 0 && y < 0

Quadrant IV: x > 0 && y < 0

This part demonstrates the importance of conditional logic in real-world scenarios.

3. Algorithm
Part A: Arithmetic, Relational & Logical Operators
Start the program.

Declare two integer variables.

Take input for both variables using cin.

Perform arithmetic operations and display results using cout.

Use relational operators to compare the two values and display outcomes.

Combine conditions using logical operators and display boolean results.

Part B: Point Location on 2D Plane
Input float values for x and y.

Check:

If x == 0 && y == 0 → Print "Origin".

Else if x == 0 → Print "Point lies on Y-axis".

Else if y == 0 → Print "Point lies on X-axis".

Else:

If x > 0 && y > 0 → Print "First Quadrant".

If x < 0 && y > 0 → Print "Second Quadrant".

If x < 0 && y < 0 → Print "Third Quadrant".

If x > 0 && y < 0 → Print "Fourth Quadrant".

End the program.

4. Procedure
Create a new C++ source file.

Include the necessary header file (#include <iostream>) and use the std namespace.

Define the main() function.

Declare required variables:

For Part A: two integers for arithmetic operations.

For Part B: two floats for coordinate input.

Take input from the user using cin.

Perform and display:

Arithmetic operations

Relational comparisons

Logical condition evaluations

Use if-else conditions to determine the location of the point in the 2D plane.

Compile and run the program.

Observe and analyze the output.

5. Sample Output Observation
Arithmetic results will show standard mathematical outputs.

Relational operators will return 0 (false) or 1 (true).

Logical operators will demonstrate combined condition results.

The coordinate logic will print messages like:

"Origin"

"On X-axis"

"On Y-axis"

"First Quadrant" etc., based on the values of x and y.

6. Conclusion
This experiment provided hands-on understanding of various fundamental C++ operators and conditional logic. It illustrated:

How arithmetic operations are performed and displayed.

The role of relational operators in comparisons.

How logical operators combine conditions.

The application of if-else statements in real-world decision-making like determining a point’s position on a 2D plane.

Together, these concepts form the building blocks of decision-making and computational logic in C++ programming.
