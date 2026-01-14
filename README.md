# C++ Fundamentals
This repository help practice the fundamental skills of C++ to a new programmer. Learn the fundamental concepts of C++ and practice the coding challenges

# C++ Language Skills:
1. Basic Syntax: Writing syntactically correct C++ programs.
2. Variables & Types: Declaring, initializing, and using variables of fundamental types.
3. I/O Operations: Using std::cout, std::cin, std::endl
4. Scope: Understanding local scope and variable lifetime
6. Multi-file Programming: Using headers, header guards, forward declarations.
7. Type Management: Understanding sizes, signed/unsigned, type casting with static_cast
8. Conditionals: Basic if statements
9. Debugging: Using debugger features (breakpoints, stepping, watch variables).

# Programming Competencies:
1. Problem Decomposition: Breaking problems into functions.
2. Code Organizations: Structuring code across multiple files.
3. Debugging Mindset: Systematic error finding and fixing.
4. Type Awareness: Choosing appropriate data types.
5. Compilation Process: Understanding build process and errors.

# C++ Fundamentals Refresher:
//Add the basic explanation of the above topics.

# Implementation Guidelines:
1. Plan first: Write pseudocode or outline
2. Start simple: Get basic functionality working
3. Add features incrementally
4. Test thoroughly: Try edge cases
5. Refactor: Improve organization, add functions
6. Document: Add comments explaining logic

# Challenges

* Challenge 1: Unit Conversion Program
-> Create a comprehensive unit conversion tool

Requirements:
-> Functions for at least 5 conversions (temperature, length, weigth, volume, time)
-> Use const for conversion factors (e.g 1 inch = 2.54 cm)
-> Multi-file organizations: separate headers for each category
-> Menu-driven interface with input validation
-> Proper data types selection

Skill tested: Functions, const, data types, organizations, user I/O

* Challenge 2: Simple Banking System
-> Simulate basic banking operations

Requirements:
-> Track balance
-> Functions for: deposit, withdraw, check balance
-> Input validations (negative deposits, overdrawing)
-> Keep transaction count and display it
-> Add interest calculation and pin verification

Skill tested: Functions, scope, conditionals, type casting, debugging

* Challenge 3: Geometry Calculator
-> Calculate properties of 2D & 3D shapes

Requirements:
-> Functions for: circle (area, circumference), rectangle (area, perimeter), triangle (area using Heron's formula), sphere (volume, surface area)
-> Use const double for n
-> Handle invalid inputs
-> Multi-files structure with clear separation
-> Menu with shape selection

Skill tested: Math operations, functions, const, error checking, organization

* Challenge 4: Health/Fitness Tracker
->Track basic fitness metrics

Requirements:
-> Calculate BMI: weight(kg) / height(m)^2
-> Calculate daily calorie needs using Miffin-St Jeor Equation
-> Track steps & convert to miles/km (2000 steps ~ 1 mile)
-> Functions for each calculation
-> Store user profile (age, weight, height, gender)
-> Add progress tracking across multiple days (simulated)

Skill tested: Complex expression, functions, data types, user interaction

* Challenge 5: Simple Quiz Game
-> Create an interactive quiz with scoring

Requirements:
-> 10 multiple-choice questions (hard-coded)
-> Track score and percentage
-> Function for: displaying questions, checking answer, calculating score
-> Use if statements for answer validation
-> Display final result with letter grade
-> Add timer simulation or difficulty levels

Skill tested: Conditional, functions, I/O formatting, logic flow

* Challenge 6: Travel Expense Calculator
-> Calcualte trip costs

Requirements:
-> Input: distance(miles/km), fuel efficiency (mpg), fuel price, hotel cost per night, food per day
-> Calculate: fuel cost, total accomodation, total food, miscellaneous
-> Functions for each calculation category
-> User appropriate data types
-> Display itemized breakdowm and total
-> Bonus: Add a functionality to add new category as well as its cost and display it in final cost display

Skill tested: Complex calcualtions, multiple functions, data types, real-world problem solving

* CHallenge 7: Number Properties Analyzer
-> Analyze mathematical properties of numbers

Requirements:
-> Input an integer
-> Determine & display: even/odd, positive/negative/zero, prime, perfect square, factorial
-> Separate function for each property check
-> Handle edge cases
-> Add palindrome check and digit sum

Skill tested: Conditionals, functions, mathematical operations, edge cases

* Challenge 8: Personal Finance Dashboard
-> Track income & expenses

Requirements:
-> Input monthly income
-> Input 5 expenses categories (rent, food, transportation, etc.)
-> Calculate: total expenses, net income, expense percentages
-> Display budget breakdowm with percentages
-> Warn if expenses exceed income
-> Use const for expense category names
-> Add savings goal tracking & time-to-reach calculation

Skill tested: Everything! Variables, types, functions, calculations, conditionals, formatting.

* Meta Challenge:
-> After completing these challenges, create a "Challenge Selector" program that:

-> Lists all your completed challenges
-> Lets user choose which to run
-> Each challenge runs as a separate functions
-> Demonstrate mastery of program organization
