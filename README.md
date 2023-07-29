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
![Alt text](/readmeImg/loginLaunch.png "Optional title")
