# Journal App

(a) 
Name of the project: Journal App
Name: Subham Kumar
BITS ID: 2018B5A70887G
Email: f20180887@goa.bits-pilani.ac.in

(b) 
A basic journal software in which the user sees the tasks he has entered on the startup screen
and, by selecting the '+' floating button, may add additional tasks with title, date, start and 
finish timings, as well as share and remove this information. The updated information is saved in 
he Room Database and presented in the start screen, and this saved job may be changed and saved 
again later. The app's information may also be seen by clicking the info button on the start screen.

(c)
Task 1:
The beginning code already included the basic nav graph design. One update was made to the info 
button in the menu bar, which redirected to the user-created info fragment. The supplied test case
failed because the position for the click was not properly stated, causing it to push the incorrect 
button, resulting in an error.

Task 2:
Columns in the database include the title, date, start time, and finish time. Aside from INSERT, 
QUERY, and UPDATE, DELETE is now provided for erasing a stored record. The aforementioned 
modifications have been made to the JournalEntry, JournalEntryDao, and JournalRepository classes.

Task 3:
A DELETE button is added to the menu bar of the EntryDetailsFragment, which only deletes a saved 
entry. Because a new item has not yet been uploaded to the database, it is not removed, and when 
the user attempts to remove a new record, an appropriate toast message is displayed. When you press
the delete button, a dialogue window displays, allowing you to accept or cancel. The entry is only 
deleted if the user hits yes.

Task 4:
On the EntryDetailsFragment view menu bar, a SHARE button has been added. It generates a plain text
message — a string of the form: "Look what I've been up to: title> on date>, start-time> to
end-time>" — and prompts the user to share it through text messaging, email, or any other 
compatible app on their smartphone. We return to the detailed view of the same entry after 
submitting. This is accomplished through the use of intent.

Task 5:
The INFO button on the EntryList fragment menu bar navigates the user to an info fragment with a 
text box containing a brief summary of the programme. The new items for the info fragment are added
to the nav graph.

Task 6:
The app's accessibility was confirmed using my phone's accessibility tester. It recommended a few
modifications to the contrast ratio of different textviews and buttons. Because no code was supplied,
no UI tests were built specifically. Instead, the UI was tested using the device's accessibility.

(d)
I used TalkBack to run the programme, and after a few trials, the experience with talk-back was rather
nice. The talk-back functionality aids in the identification of all UI components in the programme.
In addition, all of the Espresso UI tests for the different UI components succeeded.
The monkey tool did not cause the programme to crash and functioned properly.

(e) Approximate number of hours taken for me is 50 hours.

(f) Rating for this assignment in terms of difficulty is 10 out of 10.
    
    