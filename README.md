# Weather Modeling using Quadratic Equation
This project demonstrates weather modeling using a quadratic formula implemented in multiple stages.
##  Formula
T(t) = a * t² + b * t + c
Where:
- T(t) = Predicted temperature
- t = Time (hour/day)
- a, b, c = Coefficients (based on assumptions or data)
##  Versions Implemented
1. version1_hardcoded.py - Uses hardcoded coefficients and time.
2. version2_keyboard_input.py - Takes input from the user via keyboard.
3. version3_file_input_single.py - Reads a single set of values (a, b, c, t) from inputs_single.txt.
4. version4_file_input_multiple.py - Reads multiple sets from inputs_multiple.txt and prints predicted temperatures.
5. development_models.py - Simulates different software development models: Waterfall, Iterative, Agile
##  Input Files
inputs_single.txt:
0.3
-2.5
26
4
inputs_multiple.txt:
0.5 -2.0 25 3
0.4 -1.5 28 5
0.2 -0.5 30 2
##  How to Run
Run each version using Python:
python version1_hardcoded.py
python version2_keyboard_input.py
python version3_file_input_single.py
python version4_file_input_multiple.py
python development_models.py
##  Software Development Models
1. Waterfall Model - Requirement Analysis → Design → Implementation → Testing → Deployment → Maintenance
2. Iterative Model - Builds the system in small parts (iterations), improving in each step.
3. Agile Model - Uses sprints, continuous feedback, and iterative improvements.
### Example Output:
Predicted temperature at t=5: 20.50°C
##  Project Structure
weather_model_quadratic/
├── version1_hardcoded.py
├── version2_keyboard_input.py
├── version3_file_input_single.py
├── version4_file_input_multiple.py
├── development_models.py
├── inputs_single.txt
├── inputs_multiple.txt
└── README.md
