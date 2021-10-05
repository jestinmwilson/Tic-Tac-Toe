# Tic-Tac-Toe
How to run this project :

1- Download/clone the entire project and open it in IDE

   https://github.com/jestinmwilson/Tic-Tac-Toe.git
 
2- install the virtual environment

    py -m pip install --user virtualenv

3- create virtual environment
   
    py  -m venv env

4- activate the virtual environment
        
    .\env\Scripts\activate

5- Install requirements
   
    pip install -r requirements.txt

6- migrate 
   
    python manage.py migrate
    python manage.py makemigrations
7- runserver

    python manage.py runserver
    
Now you can  send game invitation to other users. When they accept your request, you can see it in Active games and play with them. Then you can play turn by turn.


