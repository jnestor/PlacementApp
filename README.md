# PlacementApp
This Java App provides a visualization of floorplanning using iterative improvement or simulated annealing.
It was originally developed as a Java Applet as part of the Lafayette College CADApplets project and ported to an application.

## PlacementApp
PlacementApp shows the placment of a set of modules on a placeemnt surface and a cost function that is a weighted sum of bounding box area, wirelength, and module overlap.  Drag a module to change its position or
click on a module to rotate it 90 degrees.  Then observe the effect on the cost function.

![Iterative Improvement Screenshot](https://github.com/jnestor/PlacementApp/blob/master/PlacementApp.png)

## IterImproveApp
IterImproveApp provides a visualization of placement improvement by iterative improvement.
When running it chooses a module at random and applies a random move (e.g., move horizontally or vertically by a random amount, rotate, or flip).  If the cost function is reduced as a result, the move is accepted.
If not, the move is reversed.  Move attempts are shown on the right hand pane; accepted moves are shaded green.

![Iterative Improvement Screenshot](https://github.com/jnestor/PlacementApp/blob/master/IterImproveApp.png)

## FloorplannerApp (Simulated Annealing)
FloorPlannerApp provides a visualization of placement improvement using Simulated
Annealing.  User can view individual moves or the overall coooling schedule (shown here)

![Simulated Annealing Screenshot](https://github.com/jnestor/PlacementApp/blob/master/FloorPlannerApp.png)
