# arcade_game_demo
game demo using arcade module in python

-->arcade.draw_triangle_filled(x1: float, y1: float, x2: float, y2: float, x3: float, y3: float, color: Union[Tuple[int, int, int], List[int], Tuple[int, int, int, int]])
-->Draw a filled in triangle.
Parameters
x1 (float) – x value of first coordinate.
y1 (float) – y value of first coordinate.
x2 (float) – x value of second coordinate.
y2 (float) – y value of second coordinate.
x3 (float) – x value of third coordinate.
y3 (float) – y value of third coordinate.
color (Color) – Color of triangle.

-->arcade.draw_lrtb_rectangle_filled(left: float, right: float, top: float, bottom: float, color: Union[Tuple[int, int, int], List[int], Tuple[int, int, int, int]])
-->Draw a rectangle by specifying left, right, top, and bottom edges.
Parameters
left (float) – The x coordinate of the left edge of the rectangle.
right (float) – The x coordinate of the right edge of the rectangle.
top (float) – The y coordinate of the top of the rectangle.
bottom (float) – The y coordinate of the rectangle bottom.
color (Color) – The color of the rectangle.

-->arcade.draw_arc_outline(center_x: float, center_y: float, width: float, height: float, color: Union[Tuple[int, int, int], List[int], Tuple[int, int, int, int]], start_angle: float, end_angle: float, border_width: float = 1, tilt_angle: float = 0, num_segments: int = 128)[source]
-->Draw the outside edge of an arc. Useful for drawing curved lines.
Parameters
center_x (float) – x position that is the center of the arc.
center_y (float) – y position that is the center of the arc.
width (float) – width of the arc.
height (float) – height of the arc.
color (Color) – color, specified in a list of 3 or 4 bytes in RGB or RGBA format.
start_angle (float) – start angle of the arc in degrees.
end_angle (float) – end angle of the arc in degrees.
border_width (float) – width of line in pixels.
tilt_angle (float) – angle the arc is tilted.
num_segments (int) – float of triangle segments that make up this circle. Higher is better quality, but slower render time.


