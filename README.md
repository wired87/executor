# executor

tech stack
- langchain
- ray

Create a langgraph based (ray.remote) agent (Admin) that creates and and manages a py venv.
The admin is able to:
- manage files and folders inisde its venv (put, del, get, update)
- run the codebase
- clone github repos inside its venv
- execute the code
- read logs
- install requirements
- receive and classify query instructions to a list of dict keys to call then the desired method on a struct: dict[identifier, runnable_method]
- all functionalities a 
