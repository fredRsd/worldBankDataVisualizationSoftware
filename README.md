# worldBankDataVisualizationSoftware
user: Admin
password: Admin123

About:

This Software fetches basic data from World Bank API, And after performing
data processing, it turns them into the requested information.

Finally, the information is shown in the requested visuals, if available:
 - Available visuals: Report, Line Chart, Bar Chart, Scatter Chart, Pie Chart

Various Object Oriented techniques and Software Design patterns are used in
the development of this project.

Introduction:

The program consists of different independent modules, which are designed to
be closed to modification but open to extension:

- login module: handles the login process
- interface modules: handle the user interface
- analysis modules: performs the required analysis of the data
- graph builder modules: produces requested visuals from the processed data
- user input module: handles user inputs (requests)
- calculation modules: contains some needed calculation methods

Description:
The program starts with running the login module:
The login module checks for valid format of the username and password, and
runs it against a credentials database. if there are errors, a meesage is
shown and program terminates:

![Alt text](/readmeImg/loginLaunch.png "loginLaunch")

![Alt text](/readmeImg/loginInvalidFormat.png "Invalid format") ![Alt text](/readmeImg/loginInvalidCredentials.png "Invalid credentials")

If login is successfull the main UI is launched:

![Alt text](/readmeImg/softwareLaunch.png "main ui launched")

The user then chooses a country, a time period for data, and the data they need
then they press recalculate button. if years are not valid, or data is not available
error messages inform the user; otherwise a meesage is shown and informs the user
that the information is calculated and ready:

![Alt text](/readmeImg/softwareUnavailableYear.png "unavailable year")

![Alt text](/readmeImg/softwareAnalysisSuccess.png "analysis done")

Then the user can select the type of visual they need and press + button.
If visual is available, it is added to the windows, and if not an error
message is shown. visuals can be removed using - button.
Repeating visuals will not be added to the window.

![Alt text](/readmeImg/softwareAnalysisVisualized.png "visuals added")
![Alt text](/readmeImg/softwareUnavailableVisual.png "visuals unavailabel")

Users can select a new country, year, or information and hit recalculate, or
terminate the program by closing it.


