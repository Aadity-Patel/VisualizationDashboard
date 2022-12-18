# VisualizationDashboard
Data Visualisation Dashboard using React as Frontend, Django as Backend and MongoDB for database.

### GENERAL SETTINGS - 

1. Make a new Folder for your Project: 
	mkdir MyProject
2. Enter the Project Folder:
	cd MyProject
3. Create environment:
         python3 −m venv projectenv 
//NOTE// Will not work with python lower version.
4. Activate the environment: 
	source projectenv/bin/activate

### BACKEND SETTINGS - Creating the Backend

1. Open VS code. In terminal again activate the environment if not activated using the same command:
		source projectenv/bin/activate
2. In activated environment install Django:
		pip install django
3. Create your Django Project:
		django−admin startproject backend 
	//backend: Name of the project
4. Enter the Django Project:
		cd backend
5. To run the server:
		python3 manage.py runserver 
6. //NOTE// The above command may give the following error: You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, content types, sessions. Run 'python manage.py migrate' to apply them.
		python3 manage.py migrate
7. Again run the server:
		python3 manage.py runserver
8. The backend server will run at http://127.0.0.1:8000/
	
	
### FRONTEND SETTINGS - Creating the Frontend

1. Open VS code. In terminal again activate the environment if not activated using the same command:
		source projectenv/bin/activate
2. Create your React Project:
		npx create−react−app frontend
	 // frontend: Name of the Project or Application.
3. Run the following command to build directory with a production build of your app
		npm run build
4. Run the server:
		npm start
5. The frontend server will run at http://192.168.0.102:3000
