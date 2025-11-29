📚 README: Adults Only! Python Adventure Picker
Project Title: Choose Your Own Adventure! (The Syndicate Courier)
NOTICE: This application is intended for users 18 years of age or older.

Overview
This project is a high-stakes, text-based Choose Your Own Adventure (CYOA) game designed to test the user’s knowledge of Python’s operator precedence and order of operations. The narrative follows an innocent protagonist who gets entangled in a dangerous web of organized crime after accepting a simple courier job.

The game forces the player to solve challenging Python equations to progress the story. Getting a math problem correct allows the story to advance, while a mistake results in immediate, negative narrative consequences (e.g., capture, betrayal, or death), creating a high-pressure, cinematic experience.

🛠️ Core Concepts & Features
This project moves beyond typical coursework by demonstrating strong practices in abstraction, modularity, and data management.

Educational Mechanism (Operator Precedence)
Purpose: The core challenge is educational. Players must correctly calculate the results of Python expressions involving unary operators, exponentiation, floor division, modulo with negative numbers, and boolean logic.

Implementation: The game uses 18 unique, non-trivial Python equations stored in a structured list of dictionaries.

Feedback: Provides detailed explanations for every correct and incorrect answer, enhancing the learning outcome.

Modularity and Control Flow
Abstractions: The entire game structure is abstracted into dedicated functions and a CHAPTER_MAP dictionary for clean, efficient branching logic.

Narrative Complexity: Features 57 distinct pathways leading to 8 unique major endings (e.g., Witness Protection, Conviction, Mob Marriage, Stand Your Ground Hero).

Randomized Questions: Uses the random and copy modules to ensure that questions are drawn randomly from the master list without repetition within a single run, adding replay value and testing flexibility.

💻 Development Notes
This project was developed as part of the 100 Days of Code Udemy course. It was a highly satisfying and challenging endeavor that pushed the boundaries of the course content, introducing practical concepts such as:

Abstraction: Creating specialized functions for logical endpoints (arrested, assassination, winner).

Modularity: Using a CHAPTER_MAP to handle complex branching across a large narrative tree.

Randomization: Utilizing random.randint and copy.deepcopy for managing the question deck efficiently.

⚠️ Content Warning
This application is intended for users 18 or older. Due to the intense, high-stakes nature of the narrative, the application includes:

Explicit depictions of gun violence and assassination.

Organized crime and coercion.

Home invasion, physical assault, and psychological distress.

Thematic elements of domestic terrorism and imprisonment.
