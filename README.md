# Drone Website
An excercise in writing CSS for a simple html markup (which can't be changed) containing two grids with 12 drone photos with descriptions.
The first layout was positioned with floats, and the second using flexbox. It should be responsive, although the layouts are pre-determined by the assignment.  
Width: 
- 1024px and up - 4 columns with first item spanning 2 columns.
- Between 600px and 1023px - 3 columns with the first two items spanning the full width.
- 600px and less - 2 columns wuth the first item spanning the whole width.
The end result can be seen at https://anis790615.github.io/float-flex_layout/.
The first version had manual widths, which resulted in items not being aligned perfectly. Redone it with calc and tested it in a new branch. Now everything works fine.
