# FirstInteractiveUI

Added two buttons names "Toast" and "Count".
Added a textView showing the number count.
When "Toast" button is clicked, a message "Hello Toast!" is shown on the screen, and when the button "Count" is clicked, the number count increases.

Changed the UI to make it compatible for different orientation and different devices.
Changed the layout to Linear and then Relative.

Renamed and Refactored the project from Hello Toast to Hello Constraint.
Added Zero button that resets the counter to 0 and changed the UI accordingly to all the layouts.

Homework Questions:

Question number 1: Which two layout constraint attributes on the Zero Button position it vertically equal distance between the other two Button elements?
a) android:layout_marginBottom="8dp"
b) android:layout_marginTop="8dp"

Question number 2: Which layout constraint attribute on the Zero Button positions it horizontally in alignment with the other two Button elements?
app:layout_constraintLeft_toLeftOf="parent"

Question number 3: What is the correct signature for a method used with the android:onClick XML attribute?
public void callMethod(View view)

Question number 4: Which of the following techniques is more efficient to use within this handler to change the Button element's background color?
Use the view parameter that is passed to the click handler with setBackgroundColor(): view.setBackgroundColor()