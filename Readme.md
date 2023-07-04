https://www.youtube.com/watch?v=riijt-xcqYI&t=616s&ab_channel=UskoKruM2010
34:20

python --version
where python
pip list	-> to see the packages installed in the environment
pip install virtualenv -> Run this to install his for your PC
python -m venv env	
	-m To run a module as a script
	venv The name of the module that allows us to create virtual environment
	env Name of the directory where the vir	tual environmente will be created
	
	NOW in your directory you are going to have "env"
	*To activate virtual environment 
	env/Scripts/activate
	*To deactivate
	deactivate

rmdir <dire_name> /s	-> to delete directory and its subdirectories
-----------------------------------------------------------------------------
pip install -r requirements.txt -> To install packages in requirements.txt

flask run -> To run flask server, This in Debug mode.
(env) PS E:\Desktop\Profesional Path\Python Profesional\first-flask-postgresql> flask run
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
127.0.0.1 - - [03/Jul/2023 15:16:48] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [03/Jul/2023 15:16:48] "GET /favicon.ico HTTP/1.1" 404 -
-----------------------------------------------------------------------------
Then we add .flaskenv
		FLASK_APP=app
		FLASK_DEBUG=True
	and add python-dotenv in requirements.txt
	reinstall requirements.txt
Now we are not in Debug mode

(env) PS E:\Desktop\Profesional Path\Python Profesional\first-flask-postgresql> flask run
 * Serving Flask app 'app'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 100-167-467
-----------------------------------------------------------------------------
python ./src/app.py

	