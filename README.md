
1. Install Anaconda 
2. Create new virtual env
3. switch focus to the new virtual env 
4. install dependencies :{
	python 3.7.13,
	tensorflow 1.14.0,
	numpy 1.21.5,
	keras 2.3.1,
	sqlalchemy,
	opencv-python 3.4.2,
	pillow,
	flask  2.0.3,
	requests,
	h5py==2.10.0
	}
	
5. go to project folder and run :
	$python initialize_db.py
6. in the browser instal the  Allow CORS extension
7. in the same project folder run:
	$python keras_server.py
8. go to browser and open 
	http://127.0.0.1:5000 
	
optionally user can use ngrok to make the app available on the internet using : 
	$.\ngrok.exe http 5000
