# Car Performance

### Context
A workshop needs to improve its management of car capabilities, so it creates classes that allow identifying the car's average performance and modifying certain parts to enhance its performance. The objective of this program is to let users create custom cars with unique values for speed, handling, acceleration, take-off, and braking ranging from 0 to 10. The program calculates the car's average performance and allows modifications to parts such as tires, chassis, engine, brakes, or drivetrain to improve or alter its performance.

### Functionality
The program prompts the user to input default values for the car, such as speed, handling, acceleration, take-off, and braking. 
It then displays the entered values and the car's average performance, along with an option to modify the car's parts. 
If the user decides to modify the car, a menu is displayed with the available parts to modify. Depending on the user's choice, the performance attributes of the car are increased or decreased.
Users can also select default car types with predefined performance values.

### Considerations
- The performance increase from modifying car parts is arbitrary and does not represent real-world precision.
- The program is developed using standard C++.
- Place the "classes" folder in the same directory as the `.cpp` file.

### Compilation and Execution
- Compile the program on Windows:
  ```bash
  g++ rendimiento_de_auto.cpp -o rendimiento_de_auto.exe
  ```

Run on Windows: "rendimiento_de_auto.exe".

Run on Linux: "rendimiento_de_auto.out".

### Fixes
The class diagram was updated to include inheritance for the classes Deportivo.h, Camper.h, and Familiar.h from the parent class Automovil.h in the "classes" folder. This change aligns with the competency "Decision-making" to properly utilize the concept of inheritance in the class diagram.
