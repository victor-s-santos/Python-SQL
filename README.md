<table>
   <tr>
      <p align="center">
        <a href="#about">About</a> •
        <a href="#how_to_run">How to run</a> •
      </p>
   </tr>
</table>

# About
> This is a repository where I am studying Python-Sql. I am aiming to solve many sql exercises, plot graphs and use the sqlalchemy orm. The main objective of this repository is to learn sql querys, functions and python, therefore the database credentials has been omitted.

# How_to_run
> To run this repository, follow the steps:
1. Create a virtualenv (this isn't necessary, but I belive this is a good practic):
    * python3 -m venv .venv `to create a virtualenv`
    * source .venv/bin/activate `to use this virtualenv`
    
2. Clone this repository:
    * git clone https://github.com/victor-s-santos/Python-SQL.git

3. Install the dependencies:
   * pip install -r requirements.txt
   
   or
   
   * pip install ipython[notebook] `to install jupyter notebook`
   * pip install python-dotenv `to install dotenv`
   * pip install pymysql `to install this pure-Python MySQL client library`

4. Open python notebook:
    * ipython notebook
    
    or
    
    * jupyter notebook
    `depending on your installation`

5. To see a Database manager:
    * Adminer
    sudo docker run \
        --name adminer \
        -p 8080:8080 \
        -d \
        adminer

now you can see your database by accessing:
http://localhost:8080/`