# bc-14-online-store

###ONLINE STORE APP
1. Sign up and sign in users.
2. Create stores when sign in. 
3. Create products associated with user store
4. Displays stores on index page with link to individual store page

### Make Use of
1. Flask Login
2. PyMongo
3. MongoDb
4. Flask

### To Use It 
1. Clone the project
2. Create a virtual environment
       
       virtualenv venv
       
3. Activate the virtual environment
  
        source venv/bin/activate
        
4. Install the requirements

        pip install -r requirements.txt
        
5. Run the app
        
        python run_dev.py
        

### App Stracture

    app
      -static/
      -templates/
      - js/
      -views.js #contain routes to render templates
      -auth.js   #contain authentications routes
      - __init__ #initializes the app
      -forms     #contains forms fields
   -config.js    #database configurations
   -run-dev.js   #start the app
   -requirements.js #contains the required modules
   
   
    
