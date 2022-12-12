# Tiles and Mines
- Tiles and Mines is single-player logic-based computer game played on rectangular board whose object is to locate a predetermined number of randomly-placed "mines" in the shortest possible time by clicking on "safe" tiles while avoiding the tiles with mines. If the player clicks on a mine, the game ends.

# Mechanics :

Mechanics 1: Understand the principles behind Tiles and Mines. Each Tiles and Mines game starts out with a grid of unmarked squares. After clicking one of these squares, some of the squares will disappear, some will remain blank, and some will have numbers on them. It's your job to use numbers to figure out which of the blank squares have mines and which are safe to click.

Mechanics 2: Use the mouse's left and right buttons. The mouse is the only tool that you'll need to play Tiles and Mines. The left mouse button is used to click squares that don't contain mines, while the right mouse button is used to flag squares that contain mines.

- On higher difficulties, you'll need to mark squares that you suspect contain mines until you can verify that they do contain mines

# UML - Unified Modeling Language

[https://drive.google.com/file/d/1DaKIhle3Hhu40wW4m1tIULpLCwAAVphI/view?usp=sharing](https://drive.google.com/drive/folders/1CN39ycwqPVWcjaVLFU-0mPSLQNb4Xr6Z?usp=sharing)

Main (Class)
----------------------------
+ main()


[Main → Cell] (Association)
Cell (Class)
----------------------------
+ all
+ cell count
+ cell count label object
+ + is_mine = is_mine
+ +is_opened = False
+ +is_mine_candidate = False
+ +cell_btn_object = None
+ + x = x
+ + y = y
+ + <<property>> surrounded_cells 
+ + <<property>>surrounded_cells_mines_lenght 
+ +<<create>> Cell()
+ +create_btn_object (location)
+ +create_cell_count_label(location)
+ +left_click_actions(event)
+ + get_cell_by_axis(x,y)
+ +show_cell()
+ +show_mine()
+ +right_click_actions_(event)
+ +randomize_mines()
+ +_repr_()


[ → Cell] (Association)
mines (Class)
----------------------------
+ + def show_mine(self):
+ +self.cell_btn_object.configure(bg='red')
+  +ctypes.windll.user32.MessageBoxW(0, 'You clicked on a mine', 'Game Over', 0)


![image](https://user-images.githubusercontent.com/118491145/206996877-90bf0c95-d974-455c-b9b4-d435cfc139ee.png)



# To run: 
- Open the main.py file to start the runtime of the program.

# Self-Assessment
| Metric        | Score           | Description |
| :-----------: |:-------------:| :----:|
| Code Reusablity | 3 | Implemented the DRY method in an acceptable manner. |
| Maintainablity  | 3 | The program's structure is based on OOP principles. Codes are readable, understandble, aiding to its maintainability |
| Scalability | 2 | The program is very difficult to scale. |
| Execution | 3 | The program works completely as intended and declared. Errors are handled properly |
| Originality | 3 | Concept is quite similar to some samples |
| Overall Impression | 4 | The program or app runs smoothly without noticeable bugs or errors. |

- total of 18/24


# Video Presentation (Demo)


# Creators of this project:
- KATRINA CYRELL MAY M. BOBADILLA
- TRISHA MAE B. MIRANDA
- PRINCESS-ANNE PABICO


- Section: IT - 2103

# Customized Module
- main
- cell
- settings
- utils

# Python-Final-Project-IT---2103

- A final project for the Course CS-121 Advance Computer Programming


