# DeweyDecimalSystemPart2
#### =============TABLE OF CONTENTS===============
1. Overview.
2. Features of the project.
3. Development dependencies.
4. Technology + software required.
5. Running of the project.
6. List of files in the directory.
7. Troubleshooting.
8. Contributors and sources.


#### ======================OVERVIEW=========================
This is an interactive application that allows librarians to be able to uniquley replace books, identify areas and find call numbers online through fun and innovative ways that essentially remove the tedious aspects of replacing books in a library. This application encompasses a unique gamified way to sort books based on their respective call numbers. In a nutshell librarians will be able to drag and drop relevant call numbers and arrange them numerically then alphabetically as well as match call numbers to descriptions and vice versa. Once they are satisfied with their arrangement they can click the check button to see if they managed to obtain the correct order all whilst being under time contrainsts. This application creates healthy competion amongst the librarians and essentially takes away from the boring aspects of their job.

The motivation behind this application was to create something a six year old will enjoy. We as humans tend to fall into the trap of living a life of routine and constant work with not rewards. This application aims to solve that, it provides a ways to bring back the fun and interesting elements of being a librarian.


#### =================FEATURES OF THE PROJECT.===================
This project includes the following:
1. A home page/ landing page in which the users will click on the task they would like to do today.
2. For now the finding call numbers button is disabled and will be implemented in the final POE.
3. A replacing books page in which the users will generate random numbers and have the ability to drag and drop them from one box to the other.
4. Instructions on how the game in the identifying areas page works.
5. An identifying areas page in which the users will match call numbers to descriptions and vice versa from column A to column B.
6. A progress bar (gamification feature) to demonstrate to the user how far they are from achieving the goal.
7. A timer (gamification feature) to bring about competion amongst the users on who sorts the fastest before the timer ticks.
8. Drag and drop validation in the event the user does not drag or drop accordingly.
9. Empty fields validation, to make sure users are selecting options in the combo boxes and not submitting empty values.
10.Toast notifications to demonstrate to the user if they have arranged the call numbers correctly.
11.Message boxes to demonstrate to the users if they have successfully matched the columns to move onto the next task.
12.Restart button to allow the user to restart the game.
13.End button to close the application.


#### =================DEVELOPMENT DEPENDENCIES.================
1. Visual studio 2019/2022
2. Toast notifications for WPF 2.5.1
3. ToastNotifications.Messages for WPF 2.5.1
4. Visual studio WPF(.NET Framework) Core 5.0


#### ===========TECHNOLOGY + SOFTWARE REQUIRED==========
1. A laptop that supports 
   windows 8, 8.1, 
   windows XP, 
   windows Vista SP 2, 
   windows 7 SPI
   windows10 and microsoft with atleast 4GB of RAM space, x86 or x84 CPU and HDD space of up to 1.5 GB available.
2. Not supported on: 
   Linux 
   MS-DOS (IBM PC DOS) 
   Windows 3.1 
   Windows NT 3.51 
   Windows 9x 
   Windows NT 4.0.
3. Microsoft visual studio 2019 version 16.9.4./ Microsoft visual studio 2022 version 17.3.4
4. .NET Framework 5.0
5. .NET Core 3.1
6. .NET 5.0
7. WPF on .NET Core 5.0


#### ============RUNNING OF THE PROJECT (INSTALLATION AND OPERATION)===================
1. Download the zipped folder(ST10122290.Prog 7312. Task 2.zip)
2. In the file explorer unzip the zipped file by extracting it.
3. Open the unzipped file.
4. Click the Library system ST10122290 file to open it.
5. Open the folder that says Library system ST10122290.Sln.
6. Visual studio 2022 will open now.
7. Once the application is opened click the green "start" button to run the application.
8. The programme will start with the home page in which the user will select the task they want to start with.
9. In this instance the user will select the identifying areas button.
10. Once this button is pressed you will be redirected to the identifying areas page.
11. On the identifying areas page the user you will click the begin button and random call numbers with their descriptions will be generated in the 2 list boxes as well as a timer will be triggered giving the user 30 seconds to complete the task..
12. The user would be required to match column A with column B by selecting the options presented in the combo boxes labelled (1,2,3,4).
13. Once satisfied with the matching, click the submit buttton to see if you have successfull matched the areas.
14. In the event that this is incorrect, a message box will appear in order for you to be able to restart the application from scratch.
15. In the event that the matching was successfuly a message box will appear in which a new question will be generated (essentially the matching of descriptions to     call numbers). The game will continue this way up until the user is not successfull or the time runs out.


#### ============LIST OF FILES IN THE DIRECTORY===================
1. When opening the zip file, open the Library system.ST10122290
2. Once opened click on the Library system.ST10122290 sln file to run the project.

--In the project there is:
1. App config 
2. App
3. App.xaml.cs with Toast theme file added (<ResourceDictionary>
                                            <ResourceDictionary.MergedDictionaries>
                                            <ResourceDictionary Source="pack://application:,,,/ToastNotifications.Messages;component/Themes/Default.xaml" />
                                            </ResourceDictionary.MergedDictionaries>
                                            </ResourceDictionary>)
4. MainWindow.xaml.cs
5. MainWindow.xaml
6. replacingBooks.xaml.cs
7. replacingBooks.xaml
8. generateClass.xaml.cs
9. identifyingAreas.xaml.cs
10.identifyingAreas.xaml
11.subsitituteIdentifyingAreas.xaml.cs
12.subsitituteIdentifyingAreas.xaml


#### ============COPYRIGHT AND LICENSING===================
1. .NET Framework generate licensce.licx.file
2. DLL references
3. NuGet packages


#### ============TROUBLESHOOTING===================
1. In the event the application crashes or stops working, make sure to restart Visual studio completely.
2. Close Visual studio and reload it, the application will reload and start working.
3. In the event the application keeps stopping, make sure you have met the mimimum dependency requirements of the application prior to running.


#### ============CONTRIBUTORS AND SOURCES===================
1. Reneilwe Motlhabi - rkmotlhabi@gmail.com - 064 630 8435
2. Jamro.K. 2018. C# Data structures and algotihms. Birmingham, Packt publishing.
3. Lilz. 2019. Interactive toast notification. 19 December 2019. [Lilz]. Available at: https://www.youtube.com/watch?v=z9GuTERyH3A
[Accessed 18 September 2022].
4. Rayhaan Nakooda. 2021. Github https://github.com/RayhaanNakooda Accessed 23 October 2022.
5.Delftstack. 2021. Get dictionary key by value in C#. Available at: https://www.delftstack.com/howto/csharp/get-dictionary-key-by-value-in-csharp/
