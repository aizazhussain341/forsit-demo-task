# forsit-demo-task
Demo task for e-commerce

**Dependencies**

Python 3.7+
Pip
Other listed in requirements.txt

**Running**

`git clone https://github.com/aizazhussain341/forsit-demo-task.git`

**Create a Virtual Environment using**

`sudo pip install virtualenv
virtualenv env`

**Activate the virtualenv**

`source env/bin/activate`

**Install dependencies**

`pip install -r requirements.txt`

Setting up environment variables

Key	               Value
DATABASE_URL	     postgresql://user:password@host:port/db

**To run the project**

`uvicorn main:app`
