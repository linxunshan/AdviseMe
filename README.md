# Senior Design 2: (Group 6) AdviseMe

## To set up a Python Virtual Enviornment:
To install virtual enviornment: 

        $ python -m pip install --user virtualenv
To create a virtual enviornment: 

        $ python -m venv env

## To run the virtual enviornment: 
**Mac OS/Linux:** 
        
        $ source /env/bin/activate
**Windows:** 
        
        $ .\env\Scripts\activate 
        
## To install dependencies: 

        $ pip install -r requirements.txt

## To check dependencies installed: 

        $ pip freeze
        
To update **requirements.txt**:

        $ pip freeze > requirements.txt 
        
## To run the application:

        $ python run.py 

The application will be running on **localhost** on **port 5000** with the following debug message: 

```
* Serving Flask app "run" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 244-552-545
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
