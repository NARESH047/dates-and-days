# dates-and-days
Quiz application on finding correct day for given date.
First, finds the number of days since epoch(01-01-1970), say it is x. 
A method generates a random integer between a range of certain negative value and the x.
Finds the epoch date equivalent of the integer and displays it.
Finds the day of the displayed date and stores it, say day1.
Calls method mentioned at line 4, then 5, then 6 and stores the resultant day, say y.
Checks if the y is x.
If yes, repeats line 7.
If no, repeats lines 7,8 to get a nonrecursive day.
Gets two more days in similar fashion.
A method generates four random number between 1 and 4.
For each day the method in line 12 is called and based on the integer corresponding to one of the four radioboxes(1-->First RadioButton) RadioButton is assigned if it is previously empty.
If not empty lines 12,13 are repeated.
Later when submit button is clicked, its checked if atleast one RadioButton is choosen.
If not, Toast conveys the message.
If yes, then text of choosen RadioBox is compared with x.
If same, then score is updated and lines from 3 are repeated.
If not same, then quiz terminates, view changes and displays final score and posts a button to try again(repeats lines from 3).
