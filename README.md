# ENGO455_SurveyTraverse
The program inside here allows the user to add a new point to the traverse and instantly calculate its coordinates. 

add_point() must be put in as either face left or as a bearing to the north

When generating the traverse the first two points should either be control points or already be known and input as Point objects with the third point being input in the constructor function in the same format as one would for add_point()

If the traverse splits it can be coppied or cut to the point in which it cuts off at and then continueing in two directions. It is reccomended to complete the survey for one traverse at a time and then to apply corrections before going back and working through a different route. This improves the precision of the points in that leg
