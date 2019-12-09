# MTConnect_testbed
MTConnect Simulator v1 : Dime Lab, North Carolina State University (windows os) Installation Steps:

Install Python 3.x on computer if not present.
1) run cmd - pip install -r requirements.txt
2) Download and install MongoDb free version with default installation parameters https://www.mongodb.com/download-center/enterprise
3) Default mongodb port 27017
4) Run the file from admin rights cmd terminal 'Code/login.py'
5) Open browser and navigate to localhost:5000/ to view app.
6) User = user, Password = dime123


To Stop simulator:
1) Click on Stop Button in http://localhost:5000/home
2) After all processess are terminated, click on Reset button to delete the Org files inside 'temp_folder'.
3)'temp_folder' should always exist and be empty before starting the simulator.
4) If files dont get deleted with reset button, delete manually inside folder.
