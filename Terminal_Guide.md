A simple, repeatable workflow to run your projects without confusion, step by step (Go to folder → Confirm location → Setup env → Install → Run) 

1) pwd (for current location of file)

2) ls (for current directory)

3) cd folder_name (to move in code file folder)

4) python -m venv venv (to create virtual environment)

5) venv\Scripts\activate (activate virtual environment)
   (we should see (venv) in terminal after above command)

6) pip install fastapi/restapi uvicorn

7) ls (to confirm the file existence)

8) uvicorn main:app --reload (to run api surver, here "main" is the file name)

9) http://127.0.0.1:8000 
   http://127.0.0.1:8000/docs (UI)

10) ctrl + c (to stop server)
