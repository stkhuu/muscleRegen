# muscleRegen
Agent-based model of skeletal muscle repair comparing localized and widespread damage. 


 INSTRUCTIONS FOR RUNNING THE REPAST MODEL
 
The Repast Simphony model contained in this archive (ABMSkeletalMuscle.zip) can be run by double clicking on the
included start_model.bat for Windows, or start_model.command for Linux or macOS. Depending 
on your Linux distribution and settings, double clicking start_model.command may be enough 
to run the model, otherwise run it from the terminal.
 
Please note that the model archive does not include a Java runtime, which must be available or be  
installed separately for the model to run. This model requires Java JDK version 11.0.16.1.
For instructions on how to check java version on Windows or Mac OS visit https://www.java.com/en/download/help/version_manual.html.
To change current java version used on Mac OS visit https://medium.com/@devkosal/switching-java-jdk-versions-on-macos-80bc868e686a.
To change current java version used on Windows visit https://www.happycoders.eu/java/how-to-switch-multiple-java-versions-windows/

After launching the Repast model with the appropriate run script described above, 
there may be a short delay before the Repast graphical user interface appears on the screen with a scenario tree showing.   

<img width="1440" alt="Screenshot 2023-01-19 at 5 02 57 PM" src="https://user-images.githubusercontent.com/118470009/213595927-4786dc62-5819-4271-86a7-e74eaaad5265.png">

First click the initialise button (looks like a power button) and wait for the geometry to load.
Next click the run button for the simulation to begin. 
Users can navigate to the parameters by clicking on the arrow in the bottom left corner. 
In this GUI, Users may change damage percentages and modes of damage. 

<img width="1440" alt="Screenshot 2023-01-19 at 5 03 07 PM" src="https://user-images.githubusercontent.com/118470009/213595992-780d074a-77db-4562-a833-f739c21f789f.png">

Note that for changes to take effect, the run needs to be stopped, the parameters must be altered and then model re-initialised and run again. 
Test this firstly by turning off localised damage and setting Localised to 0. You should then see widespread damage in place of the original.

The Repast model run controls are described in the online reference
manual here: https://repast.github.io/docs/RepastReference/RepastReference.html#_run_options .

The folder ABMSkeletalMuscle/muscleRegen also contains all agent code and necessary input files to import a model into Repast Simphony. 
For instructions on how to import a Repast model, please visit https://repast.github.io/docs/RepastReference/RepastReference.html#importing-model 
