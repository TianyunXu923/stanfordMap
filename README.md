# stanfordMap
It has following functions:
1.The map should be enclosed within a map frame (as shown above). The size, color, and style of the frame is up to you.
2.Allow the user to click and drag on the map to change the map area which is currently visible within the map frame.
3.Set the cursor to the move cursor ￼ when the user begins a drag operation. Return the cursor back to the standard arrow cursor when the drag operation is complete. You can set the cursor using the cursor style property.
4.When the user double-clicks on the map move the point double-clicked to the center of the view area.
5.The map frame should resize as the window is resized. As the window is enlarged, the map area should enlarge, as the window size is reduced the map area should be reduced. The map frame should maintain fixed margins on all sides. These margins should be maintained as the window is resized. The exact margin sizes are up to you—choose something which you find aesthetically pleasing.
6.The map should support zooming in and out. As the map zooms, the point in the center of the view area should stay fixed. In other words, if the map is centered on the Gates Computer Science building, the Gates building should stay in the center regardless of the zoom level. We’ll discuss how zooming works in more detail below.
7.Provide controls to scroll left, right, up, and down. Left or right scrolling should cause the window to scroll 1/2 of the total width currently visible. Scrolling up or down should cause the window to scroll 1/2 of the total height currently visible.
8.To keep things simple, if the user scrolls off the edges of the map it’s okay to go ahead and let them keep scrolling even if it means you can no longer see the map.
