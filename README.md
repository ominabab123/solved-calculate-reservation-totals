Download Link: https://assignmentchef.com/product/solved-calculate-reservation-totals
<br>
In this exercise, you will create a form that calculates the number of nights, total price, and average price for a reservation based on the arrival and departure dates the user enters.




<ol>

 <li>Start a new project named Reservations.</li>

 <li>Add labels, text boxes, and buttons to the default form and set the properties of the form and its controls so they appear as shown above. Controls are to have meaningful names.</li>

 <li>When the user presses the Enter key, the Click event of the Calculate button fire. When the user presses the Esc key, the Click event of the Exit button fire.</li>

 <li>Rename the form to frmReservations. When ask to modify any references to the form, click the Yes button.</li>

 <li>Add code to get the arrival and departure dates the user enters when the user clicks the Calculate button. Then, calculate the number of days between those dates, calculate the total price based on a price per night of $120, calculate the average price per night, and display the results.</li>

 <li>Declare class variables for a row counter and a rectangular array of strings that provides for 10 rows and 3 columns.</li>

 <li>Add code that stores the values for each calculation in the next row of the array when the user clicks the Calculate button. Store the total price and average price per night in currency format.</li>

 <li>Add code to display the elements in the array in a message box when the user clicks the Exit button. Use spaces and tab characters to format the message.</li>

 <li>Test the application to be sure it works correctly. At this point, the average price will be the same as the nightly price.</li>

 <li>Add an event handler for the Load event of the form. This event handler should get the current date and five days after the current date and assign these dates to the Arrival Date and Departure Date text boxes as default values. Be sure to format the dates as shown above.</li>

 <li>Modify code so Friday and Saturday nights are charge at $150 and other nights are charge at $120. One way to do this is to use a while loop that checks the day for each date of the reservation.</li>

 <li>Test the application to be sure that the default dates are displayed correctly and that the totals are calculated correctly.</li>

 <li>Code a method named IsDateTime and then add code to check that the arrival and departure dates are valid dates.</li>

 <li>Code a method named IsWithinRange and then add code to check that the arrival and departure dates are within a range that includes the minimum and maximum dates that are passed to it.</li>

 <li>Code a method named IsValidData and then add code that uses the IsPresent, IsDateTime, and IsWithinRange methods to validate the arrival and departure dates. These dates should be in a range from the current date to five years after the current date.</li>

 <li>Add code that uses the IsValidData method to validate the arrival and departure dates. In addition, add code to check that the departure date is after the arrival date.</li>

 <li>Test the application to be sure the dates are validated properly.</li>

 <li>Include a header with your name, date, and purpose of the program and meaningful comments.</li>

 <li>Zip the entire project folder before submitting to the drop box. Do not go inside the folder created when the project created. To zip right click on the folder -&gt; Click Sent to &gt; Click Compressed (zipped) folder. Do not go inside the zipped folder to run the program the program compressed. To run the program again, go back to the original folder not zipped.</li>

</ol>


