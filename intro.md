 # TIMESHEETS.

 # Using the timesheets.

The timesheets are designed to log the daily working hours of an employee over a given time period.

It has features to create, edit, delete, submit amd view of previous timesheets.
you will be able to log your daily working hours and Leave days.

![time sheet filled with some entry data](./time_doc/edit_sheet.PNG)

 ## creating a timesheet.
A time sheet is added using the `Add timesheet` button, just under your user information.

![Add a timesheet](./time_doc/timesheet_button.PNG)
	
Select a timeframe for the timesheet. and after, select `Add timesheet` to start editing the timesheet.

![Creating a timesheet](./time_doc/creationWhole.wmv)
	
After the selection, an empty timesheet is created and is to be edited for submission with your information.
there is only two fields to fill.
The day worked or holiday, and the time worked for a specific day.
	
![Empty timesheet document](./time_doc/Empty_sheet.PNG)
	
	
From the image, the input fields include the `Day worked`, all institutionally approved holidays,
including `Public holiday`, `Compassionate Leave`, `Sick Leave`, `Maternity / Partenty Leave`, `Annual Leave`
and finally `Hours` the total number of hours worked in the day.
	Note that: - **All holidays are by default given 0 hours for work time.
			   - therefore, For any given `Holiday`, this field(`Hours`) is always disabled.**
	
	
 ### Save
	The save button takes the current inputs and saves them to the database.
	This is written to the current timesheets and awaits [submission](https://LinkToTheSubmitButton)
	this means that a deletion of this saved information erases everything that has has been created sofar.
	Note that, **for a timesheet to be submitted has to first be saved.**
	
 ### Clear
	The clear button erases entry time inputs that may have been errors or wrong inputs.
	This means that unlike the delete button, the clear button only affect what has currently been
	entered and has no effect to the data that has been saved, nor that which was submitted.
	
 ### Delete
		The delete button, unlike the clear button will erase everything inthe timesheet,
		including the saved state of the timesheet.
		You have to Note that as an employee, you can not delete a timesheet once it has been submited.
		This calls you to be cautios whenn using the delete button.
		Any wrong information in the timesheets will be resent back for a review by your supervisors.
 
 ### Print
	you can print both saved and submitted timesheets..
	special to the printed document is the total work hours of the given period of time.
	
	[Print Document](./time_doc/printing.wmv)
 
 ### Submit
	The `submit` button is the final step in the timesheet creation. It updates the database and sends the created document for review by
	designated reviewers and Key acount Managers. The same shall review your submitted document and approve of the provided information.
	**This should remind you to review your timesheets thoroughly before submission.**
	 - After Submission, you lose priviledges to edit and delete any submitted timesheet.
		You however are still able to view and print a timesheet and all previously submitted timesheets in your account from the `timesheets` homepage.
	
 ### Timesheets
	This button redirects you back to the Application Homepage.

![Time_sheets home page](./time_doc/home.png)

 ## Time sheet states.
	Any submitted timesheet can be read under the following four state;
		* Draft
		* Review
		* Approved
		* Rejected


[![Time_sheet state](https://www.youtube.com/watch?v=_nm4D98VSqU)](https://www.youtube.com/embed/nm4D98VSqU)


		1. Drafted
			This is a time sheet state where the worksheet is still under editing and is not yet submitted for any form of review.
		
		2. Review
			Here, the timesheet was submtted but is under review for correctness and validity of indornation.
		
		3. Approved/Rejected
			A reviewed timesheet will follow aproval or rejection depending on the provided information.
			All rejected timesheets shall need to be reviewed by the reviewers
