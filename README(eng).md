AIMS APP TUTORIAL
=================
This tutorial will run through AIMS's User-Guide.  
The tutorial covers from an installation of AIMS to the various ways of using AIMS program.    
  
1.Installation 
--------------------------
- On AIMS website, you can download AIMS program for your Operating System (Windows OS and Mac OS support).  
  - Download: [AIMS.APCC21.ORG](http://aims.apcc21.org)   

- Setup process and User-interface are same on both Windows OS and Mac OS.  
- After the installation is finished, AIMS will auto-run and AIMS desktop icon will be created.  
  
![set-up](./set-up.png) <br/><br/>  
2.First Screen
----------------------
  
**First screen**  
- You can create a new project by clicking **'+New Project'** Icon.
- On the right side, there is a **News Feed**, which contents are related to AIMS.
- If you want to change AIMS program settings, '⚙' icon is located on right corner of the screen.  

![first-main](./first-main.png)  
  
  
**Application Preference screen**  
- By clicking '⚙' icon, you can change **Workspace Directory** and **Database Directory**.  
  - *Workapce Directory* = Directory for saving project
  - *Database Directory* = Directory for saving shared data for project  
 
- You can simply log off by clicking **'Log Off'** button.  
   
![application-preference](./application-preference.png)  
  
  
3.Create a new project
---------------- 
**Create a new project screen**  
- In order to create a new project, you need to select a project type and enter a project name.  
  
![create-a-new-project](./create-a-new-project.png)

**Project Selection Screen**  
- Select a project you wish to run. 
  
![project](./project.png)  
  
**Project Screen(1-a)**  
The screen represents the view of your selected project screen  
  
- **'🏠'** icon is located on the left corner, by clicking it you can retrieve to the *first page*.  
- **'▶'** icon and **↻** icon are located on top of the middle.  
  - **'▶'** icon: Run a project  
  - **'↻'** icon: Restart a project  
- On right side of the screen, you can find out project name and description.  

  ![project-main-1](./project-main-1.png)  
    	
**Project Screen(1-b)**  
The screen represents the view of *Project Screen(1-a)*, and right side tab is scrolled down.  
  
- On right side of the screen, you can find out package information.  
  - Package information contains name, version, and dependencies.  
  
- *Export and Upload Buttons*  
  - By clicking **'Export'** button, you can save a current project result as (000.aims.proj) format.  
  - By clicking **'Upload to Aims-web'** button, you can upload a current project result to Aims-web.  

- *Reset Buttons*  
  - By clicking **'Reset Workflow Status'** button, you can refresh all workflow status.  
  - By clikcing **'Reset All Settings'** button, you can reset all settings.  
  
![project-main-2](./project-main-2.png)  
  
  
4.Project Card Settings  
------------------
Each card in project contains unique task(Operation Algorithm), and it starts from top to bottom during execution.  
  
  
**Obejective Selection Setting**  
- Select one or multiple objectives  
  
![objective](./objective.png)  
  
**Data Source Setting**  
- Select one or more data sources  
- Select a region  
  
![data-source](./data-source.png)  
  
**Local Data Setting**  
- Preparing custom local data files
  - Save and change station data template (.csv)file  
  - Save and change observation data template (.csv)fiie  
- Import template files
  - Click **Import Template files** button, when you ready for station data and observation data file.  
  
![local-data](./local-data.png)  
![local-data-2](./local-data-2.png)  
  
**Evaluate Obeserved Data Setting**  
- Select one or more variables  
- Enter start year and end year for observed type
  
![evaluate observed data](./evaluate%20observed%20data.png)  
  
**Process Stopper Setting**  
- **Unclicked**: Program will be stop at the point where the process stopper is unclicked.  
![stop](./stop.png)  
  
- **Clicked**: Program will be executed without interference.  
![stop-2](./stop-2.png)  
  
**Downscale Setting**  
- Select GCM names  
- Select Scenario  
- Select one or more variables  
- Enter start year and end year for each type [Observed, Historical(GCM), Future(GCM)]
- Select one or multiple downscale methods  
  
![downscale](./downscale.png)  
  
**Climate-change-index-calculation**  
- Select one or multiple GCM names  
- Add a custom index by your needs  
  
![climate-change-index-calculation](./climate-change-index-calculation.png)
![climate-change-index-calculation-2](./climate-change-index-calculation-2.png)  
  
**Weight-factor-and-uncertainly-for-GCMs**  
- Select one of multiple indices  
- Choose one downscale method  
  
![weight-factor-and-uncertainly-for-GCMs](./weight-factor-and-uncertainly-for-GCMs.png)
![weight-factor-and-uncertainly-for-GCMs-2](./weight-factor-and-uncertainly-for-GCMs-2.png)  
  
**Modeling-drought-index**  
- Select one or multiple GCM names, by clicking **'ADD'** button  
- Enter start year and end year for calibration type  
  
![modeling-drought-index](./modeling-drought-index.png)
![modeling-drought-index-2](./modeling-drought-index-2.png)  
  
**References**
- This card contains all references that has been used in a current project  
  
![references](./references.png)  
  
  
5.Project Execution
---------------------
- After finishing project card settings, you can execute the project.  
- First execution can possibly be slow, due to sub-package dependences have not been installed yet.  
- If you execute a project, all other buttons will be inactivated except **'Play and Stop'** Button.  
  
![project-start-1](./project-start-1.png)  
  
**Notification during Execution**  
- **'Running'** status expresses that the current card is running  
  
![project-start-2](./project-start-2.png)  
  
- **'error'** status expresses that the current card has been errored
  - If the error occurs, you can open log file by clikcing **'⋮'** button.  
  
![project-start-3](./project-start-3.png)  

- If you wish to execute single card, you can click **'run-this-section-only'**.  
  
![run-this-section-only](./run-this-section-only.png)  
