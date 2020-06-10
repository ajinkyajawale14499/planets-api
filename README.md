# planets-api
CRUD - Flask rest api implementation in python with SQLite database (RDBMS)

Intructions:

1) create python3 venv

  1.1) sudo apt install python3-venv
  1.2) python3 -m venv my-project-env
  1.3) source my-project-env/bin/activate
  
2) install dependencies

  pip install -r requirements.txt
  
  ( -r will remove previous package if present and install package version metioned in requirement.txt file )
 
3) install DB Browser for SQLite for better understanding of your DB maintain it well :)
 
      sudo apt-get install sqlitebrowser
  
4)create a SQLite Database

#python3

#database models
class User(db.Model):
    __tablename__ = 'users'
    # db fields ...

#database models
class User(db.Model):
    __tablename__ = 'users'
    # db fields ...
    
4) flask run :)
    
    

  
