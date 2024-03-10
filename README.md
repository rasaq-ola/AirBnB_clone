0x00. AirBnB clone - The console
## Description of the project
- A AirBnB console that should work as shouwn below in interactive mode
 (hbnb) help

 Documented commands (type help <topic>):
 ========================================
 EOF  help  quit

 (hbnb) 
 (hbnb) 
 (hbnb) quit
 $
- But also works as though in a non-interactive mode
 (hbnb)

 Documented commands (type help <topic>):
 ========================================
 EOF  help  quit
 (hbnb) 
 $
 $ cat test_help
 help
 $
 $ cat test_help | ./console.py
 (hbnb)

 Documented commands (type help <topic>):
 ========================================
 EOF  help  quit
 (hbnb) 
 ZZzz$-
