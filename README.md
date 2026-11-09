# EX No.3.2. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:
## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

1. Click Create Sketch and select the XY Plane (Front Plane).

<img width="507" height="568" alt="Screenshot 2026-11-08 233147" src="https://github.com/user-attachments/assets/2a38506b-0c56-4ba6-9423-9ee5199a6cbc" />

2. Draw a Center Diameter Circle centered on the origin with a radius of 110 mm (Diameter = 220 mm).

<img width="363" height="461" alt="image" src="https://github.com/user-attachments/assets/f19e980f-21fb-4a96-93d6-9872d22a0e55" />

3. Draw a horizontal line from the left quadrant to the right quadrant to split it in half, then use the Trim tool (T) to delete the bottom half, leaving a perfect semicircle arch.

<img width="363" height="461" alt="image" src="https://github.com/user-attachments/assets/02ac68ac-a393-4253-9d70-2367de896d54" />

4. Draw a 2-Point Rectangle inside the arch starting from the bottom horizontal line to form the cutout, with a width of 120 mm and a height of 60 mm (horizontally centered).

<img width="363" height="461" alt="image" src="https://github.com/user-attachments/assets/04ad9c41-7a1c-44c1-a2a7-52a73f20ed09" />

5. Use the Trim tool (T) to cut away the bottom line of the semicircle inside this rectangle, combining the inner arch and cutout into one single profile.

<img width="197" height="310" alt="image" src="https://github.com/user-attachments/assets/0aa4e6dd-2317-416e-b7e4-978e2385efe5" />

6. Click Finish Sketch in the top right corner.

<img width="201" height="170" alt="Screenshot 2026-10-11 174217" src="https://github.com/user-attachments/assets/30997493-b1f4-4196-80d1-814180e037e4" />

7. Select Extrude (E), click your arched profile, extrude it to a total depth of 150 mm, and set the operation to New Body.

<img width="503" height="605" alt="Screenshot 2026-11-03 211338" src="https://github.com/user-attachments/assets/c1a15a7b-4fc0-4acb-9757-f4e650d279a1" />

8. Go to the top toolbar, click on the Construct dropdown menu, and select Offset Plane.

<img width="609" height="481" alt="image" src="https://github.com/user-attachments/assets/5b5b3b15-ee86-47c0-84a6-b4bc3d7be30f" />

9. Click on the flat, interior vertical wall inside the semicircular cutout, set the distance to position the plane where the interior step begins, and click OK.

10. Select Create Sketch and click directly on this newly created Offset Plane.

<img width="507" height="568" alt="Screenshot 2026-11-08 233147" src="https://github.com/user-attachments/assets/86dba2ed-786a-4990-9f48-6d8a9ce69fc9" />

11. Draw a 2-Point Rectangle extending outwards to form the side flange with a width of 120 mm and a height of 30 mm.

12. Draw a Center Diameter Circle with a diameter of 40 mm (Ø40mm) on this flange face, using the Sketch Dimension tool (D) to position its center exactly 150 mm away from the center axis of the part.

13. Click Finish Sketch.

14. Select Extrude (E), click the rectangular face (leaving the 40 mm circle profile unselected so the hole is automatically left open), and extrude it straight back into the main body so it merges, setting the operation to Join.

15. Select the Fillet tool (F) from the Modify menu, click the outer vertical edges of this extruded rectangle, and type in 60 mm to perfectly round out the outside shape.

<img width="539" height="566" alt="image" src="https://github.com/user-attachments/assets/5db89912-27e9-4eeb-9628-018a17c48827" />

16. Go to the top toolbar, click the Create menu dropdown, and select Mirror.

<img width="543" height="762" alt="image" src="https://github.com/user-attachments/assets/e2bb7c9d-5803-4da9-8058-3b5f9a458eae" />

17. In the Mirror dialog box, set the Object Type to Features or Bodies, select the flange extrusion, the hole cut, and the fillets from your timeline.

18. Click Mirror Plane in the dialog box, select the central YZ Plane (or the midplane of your arched block), and click OK to instantly replicate the complete flange on the other side.

19. Select Create Sketch, click on the top flat apex of the main center arch, draw a 20 mm (Ø20mm) circle in the absolute center, finish the sketch, and Extrude Cut it straight down through the top wall.

20. Click the Save icon at the top left and name your file (e.g., "ex 3.2 Bearing Bracket Mirror Workflow").

22.Complete the 3D model and save the design.Select Design → Drawing → From Design.

<img width="284" height="453" alt="696496081-bdd3c885-03b4-406b-a390-ab4d83b96a92" src="https://github.com/user-attachments/assets/549e2f44-e728-4ebf-b47f-3f6180a62d14" />
<img width="415" height="462" alt="696496745-a76e1fa1-d3e9-4f02-b1cc-59c60129e578" src="https://github.com/user-attachments/assets/5ee7cd3b-a32a-45ee-bf9a-9c0622301e38" />


## INPUT:

<img width="810" height="567" alt="image" src="https://github.com/user-attachments/assets/b1d1f0cd-d35b-4354-bc0e-2c5762edb3ec" />


## OUTPUT:

<img width="1525" height="717" alt="Screenshot 2026-11-02 114452" src="https://github.com/user-attachments/assets/e3261c3a-5408-40bd-b1d9-307b87984949" />

<img width="810" height="567" alt="image" src="https://github.com/user-attachments/assets/dcde2691-3dcc-4dbe-ad58-c0c4dd27bc73" />


## RESULT:
Thus, 3D model is created from orthographic projection.



