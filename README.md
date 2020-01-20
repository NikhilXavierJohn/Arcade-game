# arcade_game_demo
game demo using arcade module in python

--><b>arcade.draw_triangle_filled(x1: float, y1: float, x2: float, y2: float, x3: float, y3: float, color: Union[Tuple[int, int, int], List[int], Tuple[int, int, int, int]])<b><br>
-->Draw a filled in triangle.<br>
Parameters<br>
x1 (float) – x value of first coordinate.<br>
y1 (float) – y value of first coordinate.<br>
x2 (float) – x value of second coordinate.<br>
y2 (float) – y value of second coordinate.<br>
x3 (float) – x value of third coordinate.<br>
y3 (float) – y value of third coordinate.<br>
color (Color) – Color of triangle.<br>

-->arcade.draw_lrtb_rectangle_filled(left: float, right: float, top: float, bottom: float, color: Union[Tuple[int, int, int], List[int], Tuple[int, int, int, int]])<br>
-->Draw a rectangle by specifying left, right, top, and bottom edges.<br>
Parameters<br>
left (float) – The x coordinate of the left edge of the rectangle.<br>
right (float) – The x coordinate of the right edge of the rectangle.<br>
top (float) – The y coordinate of the top of the rectangle.<br>
bottom (float) – The y coordinate of the rectangle bottom.<br>
color (Color) – The color of the rectangle.<br>

-->arcade.draw_arc_outline(center_x: float, center_y: float, width: float, height: float, color: Union[Tuple[int, int, int], List[int], Tuple[int, int, int, int]], start_angle: float, end_angle: float, border_width: float = 1, tilt_angle: float = 0, num_segments: int = 128)[source]<br>
-->Draw the outside edge of an arc. Useful for drawing curved lines.<br>
Parameters<br>
center_x (float) – x position that is the center of the arc.<br>
center_y (float) – y position that is the center of the arc.<br>
width (float) – width of the arc.<br>
height (float) – height of the arc.<br>
color (Color) – color, specified in a list of 3 or 4 bytes in RGB or RGBA format.<br>
start_angle (float) – start angle of the arc in degrees.<br>
end_angle (float) – end angle of the arc in degrees.<br>
border_width (float) – width of line in pixels.<br>
tilt_angle (float) – angle the arc is tilted.<br>
num_segments (int) – float of triangle segments that make up this circle. Higher is better quality, but slower render time.<br>


