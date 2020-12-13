# Vertical Measurements Program
*This is a demo project for "CE-UY 3013 Computing In Civil Engineering". It's purpose is to check the adequacy of Vertical Measurements taken before a Site Layout.
* 

This program is intended to run when there is a CSV file that is uploaded with 5 columns and 6 rows. This means it is limited to a survey that has only 4 points, like in this case A through D. The first column has the names of the points, this can be letters or specific names. For instance, instead of point A, a surveyer could indicate point A to be an item like a tree or some sort of permanent monument to indicate where it was taken. The second solumn, abbreviated as BS (+) is the Backsight, and this is the first sight taken with a leveling staff, there is only one backsight and the rest of the values are zero for backsight afterwards. The next column is the H.I. which is the height of the instrument, which is constant throughout the experiment. The F.S. is the Fore Sight, which is the last staff reading taken (There is a minus because Foresight is considered "minus sight"). The last column in this CSV file is the Length of the Course, which is the distance between the point and the one right before it.

Inputs:
* start & end coordinates of each member
* vertical and/or horizontal load at joint with coordinates (x,y)

Outputs:
* New CSV file with adjusted elevations
* Adequacy of selected measurements
* Graph of the selected points if they are adequate


![Screenshot of Excel Sample](https://user-images.githubusercontent.com/69228228/102020387-eb52a880-3d46-11eb-8e75-94027ca8d8ed.png)
