## Studio Ghibli Movie Explorer: 

[Data Structures FP Repo](https://github.com/sigreipel/DataStructures-Final-Project)

_Studio Ghibli Movie Explorer_ is an interactive program designed to retrieve and display information about Studio Ghibli films. The JSON data is obtained from the [Studio Ghibli API](https://ghibliapi.vercel.app/#), parsed into python data structures, sorted the films alphabetically using the insertion sort algorithm, and presented through a GUI built with Tkinter.

<ins>Features:</ins>
  API Integration
  
  - Retrieves live movie data from the Studio Ghibli API.
  - Parses JSON into Python data structures (lists and dictionaries).
  
  Sorting Algorithm
  
  - Implements a custom insertion sort for ordering movies alphabetically by title.
  - Reinforces understanding of algorithm design and efficiency trade-offs.
  
  Graphical User Interface
  
  - Tkinter-based interface to display film details, including title, director, release date, and description.
  - Provides structured and user-friendly movie browsing.
  
  Data Structures
  
  - Lists used for managing collections of movie objects.
  - Dictionaries used for storing individual movie attributes.
  
  <ins>TechStack:</ins>
  
  Language: Python
  
  Libraries: Tkinter, Requests (for API calls), JSON
  
  Algorithm: Insertion Sort
  
  <ins>Future Improvements</ins>
  
  - Replace with a more efficient algorithm (e.g., merge sort or quicksort) for scalability.
  - Add filtering or searching functionality by director, release year, or rating.
  - Expand the GUI with images, better layout, and improved interactivity.
  - Cache or locally store API results to improve performance and usability offline.
