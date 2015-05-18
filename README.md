#Description
This is a youtube download link generator based on `flask-heroku` and the python package `pytube` meant for deploying on heroku.

#Instructions
To dev:
+ `pip install -r requirements.txt`
+ `python app.py`
+ viola
+ you may also use heroku toolbelt's program foreman if you get fancy with the heroku process management (want to define more processes in procfile) /want to test with gunicorn. run `foreman start` to use this. If you only have the one web process, `python app.py` is recomended because it restarts on detected code change, a useful thing for test based developement, you should try `foreman start` before pushing, though, just to make sure it will work on heroku'

#Link
This code is deployed at https://aqueous-oasis-5124.herokuapp.com/

