# Running Instructions and User Manual:

To run our solution open all files in this ZIP file in UiPath Studio. This solution was tested and developed primarily in UiPath Academic Alliance Studio 2022.4.1 and up and we strongly recommend running it in these versions as we can make no promises to the performance of the solution if run in other versions.

Microsoft Edge must also be installed alongside its UiPath extension. A tutorial is shown in this link: https://docs.uipath.com/studio/standalone/2023.4/user-guide/extension-for-edge-chromium. The solution will not run properly without them.

Once the files have loaded, run our solution by opening the ‘GrossIteration.xaml’ file and then clicking Run/Run File/Debug. It will take some time to run entirely but once it has finished, open up ‘Movie_Data.xlsx’ where you will find the title, url, rank, director, studio and producer information for each movie in the sheet ‘MovieInfo’ and the name and highest grossing movie (and the corresponding gross amount) for each director in ’Directors’.

It is important not to have ‘Movie_Data.xlsx’ open while the solution is running.
For logging data please move the 'LoggingMessages.xlsx' to another location before running so that the process can generate a new log for each new runtime. The log messages will include a time stamp, information and log level.

We also have some test cases to check that our scraping is working correctly. They do not run automatically so to test them open the Test Explorer Panel (bottom right of screen - see picture) and then click Run all.

![testexplorer](https://github.com/psri981/Group8-300-762/assets/79731335/d36d9995-3689-4c25-bb44-95c94b336e50)

Our project repo and commit history is available here:
https://github.com/psri981/Group8-300-762.git
