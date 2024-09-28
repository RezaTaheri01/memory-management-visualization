* * *
* * *

# Memory Management Visualization

This project is a memory allocation simulator built using JavaScript. It provides a visual representation of memory management techniques like First Fit, Best Fit, Next Fit, and Worst Fit.

# Preview
https://github.com/user-attachments/assets/e15e7c72-47f8-4105-94bd-af8d96b4d306


Features
--------

* Memory Visualization: Displays memory blocks in two views: Stable (V1) and Dynamic (V2).
* Dynamic Allocation: Allocate memory using different fit strategies.
* Interactive UI: Add or remove memory programs via an intuitive interface.
* Memory Fragmentation Awareness: Track memory waste and optimize allocation.
* SweetAlert Integration: For user input and error handling.

How it work
------------

1. **Memory Size**: Choose the memory size (in kB) using the slider when starting the simulation.
2. **Add Memory**: Enter the program size and select one of the allocation methods:

    * First Fit
    * Best Fit
    * Next Fit
    * Worst Fit
      
4. **View Memory**: The allocated memory is displayed with visual animations.
5. **Remove Programs**: Double-click on any program block to deallocate it.
6. **View Memory Details**: The detailed allocation table provides program sizes, start/end addresses, and memory waste.


Setup
------------
1.  **Clone the repository:** 
    ```
    git clone https://github.com/RezaTaheri01/memory-management-visualization.git
    ```
 
 2. Open **index.html** in your browser to run the simulation.
    
 It also accessible from https://reza-taheri.ir/home/memory/

 Dependencies
------------
* **SweetAlert** for alerts and input dialogs.
* **jQuery** for DOM manipulation and animations.


Contributing
------------
Feel free to submit issues and pull requests to help improve this project!


License
------------
This project is licensed under the MIT License.
