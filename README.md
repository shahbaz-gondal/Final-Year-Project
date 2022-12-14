
# Django Simple E-Commerce Website (ENursery)
This is a simple E-Commerce website built with Django (Python) 


### Admin Users Can
1. Manage Category (Add, Update, Filter and Delete)
2. Manage Products (Add, Update, Filter and Delete)
3. Manage Users (Update, Filter and Delete)
4. Manage Orders (View and Process)

### Non-Registered Users Can
1. View Products (Can filter based on Categories)
2. Explore Product Details


### Registered Users Can

1. Add to Cart
2. Checkout
2. See the Order Status
3. Update Profile 
4. Reset Password

### Installation
** Create a Folder where you want to save the project**

** Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv

```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

Then, Enter the project
```
$  cd project
```

 ** Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```




** Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```

```
Create Super User 

Command for PC:
```
$  python manage.py createsuperuser
```
