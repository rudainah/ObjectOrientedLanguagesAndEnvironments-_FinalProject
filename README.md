1.	About this Project

The Study Hours Tracker is an Object-Oriented Programming (OOP) Python application designed to help students track their weekly study hours for various subjects. It provides a user-friendly interface built using the Tkinter library and utilizes SQLite for data storage. The application adopts an OOP approach to structure its components, promoting modularity, reusability, and maintainability. Users can input their grade and the hours they've studied for each subject, after which the application generates personalized feedback and performance reports based on the input data.

2.	Technologies Used:

-	Tkinter (GUI toolkit)
-	SQLite3 (database management)
-	Matplotlib (for data visualization)

3.	 Classes and Methods

•	study_hours_tracker.py

-	create_login_widgets(self)
-	create_main_widgets(self)
-	create_subject_widgets(self)
-	show_login(self)
-	show_main(self)
-	show_subjects(self)
-	logout(self)
-	show_welcome_message(self)
-	login(self)
-	register(self)
-	create_subject_widgets(self)
-	show_subjects(self)
-	avg(self, hours)
-	show_summary(self)
-	avg_report(self, user_avg, system_avg)
-	summary_report(self, user_hour, system_hour)
-	plot_summary(user_hours, system_hours, subjects)

-	setup_database()
-	save_to_database(grade, user_hours, user_avg, system_avg, avg_result, summary_results)

•	main.py

-	It contains the main method to start the application.



4.	Features 

•	User Authentication:
-	Users can register with a username and password or log in if they already have an account.
-	Authentication is managed securely through SQLite3 database.

•	Tracking Study Hours:
-	Users can input their study hours for different subjects based on their grade level.
-	The application displays a list of subjects based on the user's grade selection, allowing for easy data entry.

•	Weekly Summary:
-	After entering study hours, users can view a summary report comparing their study hours with recommended hours.
-	The summary report includes the weekly average of study hours, personalized feedback on study performance, and suggestions for improvement.

•	Data Visualization:
-	The application generates a bar chart visualization to compare the user's study hours with recommended hours for each subject.
-	Matplotlib library is used for creating interactive and informative visualizations.
