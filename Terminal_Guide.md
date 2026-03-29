A simple, repeatable workflow to run your projects without confusion, step by step (Go to folder → Confirm location → Setup env → Install → Run) 

pwd (for current location of file)

ls (for current directory)

cd folder_name (to move in code file folder)

python -m venv venv (to create virtual environment)

venv\Scripts\activate (activate virtual environment)
(we should see (venv) in terminal after above command)

pip install fastapi/restapi uvicorn

ls (to confirm the file existence)

uvicorn main:app --reload (to run api surver, here "main" is the file name)

http://127.0.0.1:8000 
http://127.0.0.1:8000/docs (UI)

ctrl + c (to stop server)
