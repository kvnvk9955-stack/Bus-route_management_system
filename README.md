
```markdown
# Bus Route Management System

A simple C++ program implementing a bus route management system using a **doubly linked list**. This project demonstrates the practical application of dynamic data structures for real-world route and station management.

Supports adding, inserting, deleting, searching stations, and displaying the route in both forward and backward directions.

---

## Features

- Add new stations to the route
- Insert a station at a specific position
- Delete an existing station by name or ID
- Search for a station in the route
- Display the route from start to end (forward direction)
- Display the route from end to start (backward direction)

---

## Data Structure Used

**Doubly Linked List**  
Each node (station) contains:
- Station name
- Station ID / code
- Pointers to both the next and previous stations

This allows traversal in both directions, making the system efficient and intuitive for route management.

---

## How to Run

1. Compile the code using any C++ compiler (e.g., g++):
   ```bash
   g++ ROUTE.cpp -o bus_route
   ```

2. Run the executable:
   ```bash
   ./bus_route
   ```

3. Follow the on-screen menu to manage the bus route.

---

## Sample Output

(Refer to the screenshots in the repository for visual examples)

```
--- Bus Route Management System ---
1. Add Station
2. Insert Station at Position
3. Delete Station
4. Search Station
5. Display Route (Forward)
6. Display Route (Backward)
7. Exit
Enter your choice: 1
Enter station name: Central Bus Stand
Enter station ID: 101
Station added successfully.
```

---

## Project Structure

```
Bus-route_management_system/
├── ROUTE.cpp                 # Complete source code
├── ROUTE.exe                 # Compiled executable (Windows)
├── README-2.md               # Original README
├── Screenshot 2025-12-08 113519.png
├── Screenshot 2025-12-08 113554.png
└── Screenshot 2025-12-08 113614.png   # Sample output screenshots
```

---

## Future Scope

- Add file handling to save and load routes
- Implement fare calculation between stations
- Add multiple bus routes with different schedules
- Create a graphical user interface (GUI)
- Integrate with maps for real-time navigation

---

## Author

**K.V.N Vamsi Krishna**  
AP24110010693  
SRM University, AP

---

## License

This project is for educational purposes as part of an academic course requirement.
```

This README focuses on the key aspects of your project: the doubly linked list implementation, route management features, and how to run the program. 
