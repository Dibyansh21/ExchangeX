## ExchangeX

+ Connect with currencies worldwide

* Created by 
    + [Harsh Tripathi](https://github.com/Harsh324)
    + [Arjun Kumar](https://github.com/Harsh324)
    + [Nilay Singh](https://github.com/Harsh324)
    + [Ajay Saini](https://github.com/Harsh324)

---

## Github
One Can Use Portal on Your system . Program is uploaded on github

You can go to Github [Github_Repository](https://github.com/Harsh324/ExchangeX)

---
## API

---

## Package [Exchange](https://github.com/Harsh324/ExchangeX/tree/main/Exchange)

### Hierarchy is as  shown

```
Exchange
├── exchange
│   ├──__pycache__
│   │    ├──__init__.cpython-310.pyc
│   │    ├──exchange_functions.cpython-310.pyc
│   ├──__init__.py
│   └──exchange_functions.py
├── tests
│   ├── __init__.py
│   └── test_functions.py
├──README.md
└──setup.py

```
---
## Importing Package [Exchange](https://github.com/Harsh324/ExchangeX/tree/main/Exchange)

```py
import Exchange.exchange.exchange_functions as Ex
exchangeObj = Ex.Exchange()
```
+ Exchange Package Contains
    * [exchange](https://github.com/Harsh324/ExchangeX/tree/main/Exchange/exchange) Package

---
+ This Module contains 4 methods
as mentioned in upcoming slides

---

* Function [parse_api()](https://github.com/Harsh324/ExchangeX/blob/main/Exchange/exchange/exchange_functions.py)
+ Can be called as  ,
```py
exchangeObj.parse_api()
```
![](Img/Img1.jpg)


---

* Function [currencies()](https://github.com/Harsh324/ExchangeX/blob/main/Exchange/exchange/exchange_functions.py)
+ Can be called as  ,
```py
exchangeObj.currencies()
```
![](Img/Img2.jpg)


---

* Function [get_rate()](https://github.com/Harsh324/ExchangeX/blob/main/Exchange/exchange/exchange_functions.py)
+ Can be called as  ,
```py
exchangeObj.get_rate()
```
![](Img/Img3.jpg)




---

* Function [convert()](https://github.com/Harsh324/ExchangeX/blob/main/Exchange/exchange/exchange_functions.py)
+ Can be called as  ,
```py
exchangeObj.convert()
```
![](Img/Img4.jpg)

---


## Package [Kyc](https://github.com/Harsh324/ExchangeX/tree/main/Kyc)
### Hierarchy is as  shown 

```
Kyc
├── kyc
│   ├──__init__.py
│   └──kyc_functions.py
├── tests
│   ├── __init__.py
│   └── test_functions.py
├──README.md
└──setup.py

```
---

## Importing Package [Kyc](https://github.com/Harsh324/ExchangeX/tree/main/Kyc)

```py
import Kyc.kyc.kyc_functions as Ky
kycObj = Ky.Kyc()
```
+ Kyc Package Contains
    * [kyc](https://github.com/Harsh324/ExchangeX/tree/main/Kyc/kyc) Package
---
+ This Module contains 1 Functions 
as mentioned in upcoming slides

---
* Function [addToDatabase()](https://github.com/Harsh324/ExchangeX/blob/main/Kyc/kyc/kyc_functions.py)
+ Can be called as  ,
```py
kycObj.addToDatabase()
```
![](Img/Img5.jpg)

---



## Package [Login](https://github.com/Harsh324/ExchangeX/tree/main/Login)
### Hierarchy is as  shown 

```
Login
├── login
│   ├──__init__.py
│   └──login_functions.py
├── tests
│   ├── __init__.py
│   └── test_functions.py
├──README.md
└──setup.py

```
---
## Importing Package [Login](https://github.com/Harsh324/ExchangeX/tree/main/Login)

```py
import Login.login.login_functions as Log
logObj = Log.Login()
```
+ Login Package Contains
    * [login](https://github.com/Harsh324/ExchangeX/tree/main/Login/login) Package

---
+ This Module contains 2 Functions 
as mentioned in upcoming slides

---

* Function [validateUser()](https://github.com/Harsh324/ExchangeX/tree/main/Login/login/login_functions.py)
+ Can be called as  ,
```py
logObj.validateUser()
```
![](Img/Img6.jpg)


---

* Function [register()](https://github.com/Harsh324/ExchangeX/tree/main/Login/login/login_functions.py)
+ Can be called as  ,
```py
regObj = Log.Register()
regObj.register()
```
![](Img/Img7.jpg)


---

## Package [Payment](https://github.com/Harsh324/ExchangeX/tree/main/Payment)
### Hierarchy is as  shown 

```
Payment
├── payment
│   ├──__init__.py
│   └──payment_functions.py
├── tests
│   ├── __init__.py
│   └── test_functions.py
├──README.md
└──setup.py

```
---
## Importing Package [Payment](https://github.com/Harsh324/ExchangeX/tree/main/Payment)

```py
import Payment.payment.payment_functions as Py
paymentObj = Py.Payment()
```
+ Payment Package Contains
    * [payment](https://github.com/Harsh324/ExchangeX/tree/main/Payment/payment) Package

---
+ This Module contains 3 Functions 
as mentioned in upcoming slides

---


* Function [connect()](https://github.com/Harsh324/ExchangeX/tree/main/Payment/payment/payment_functions.py)
+ Can be called as  ,
```py
paymentObj.connect()
```
![](Img/Img8.jpg)


---

* Function [transaction()](https://github.com/Harsh324/ExchangeX/tree/main/Payment/payment/payment_functions.py)
+ Can be called as  ,
```py
paymentObj.transaction()
```
![](Img/Img9.jpg)


---

* Function [disconnect()](https://github.com/Harsh324/ExchangeX/tree/main/Payment/payment/payment_functions.py)
+ Can be called as  ,
```py
paymentObj.disconnect()
```
![](Img/Img10.jpg)


---



## Package [Taxation](https://github.com/Harsh324/ExchangeX/tree/main/Taxation)
### Hierarchy is as  shown 

```
Taxation
├── taxation
│   ├──__init__.py
│   └──taxation_functions.py
├── tests
│   ├── __init__.py
│   └── test_functions.py
├──README.md
└──setup.py

```
---
## Importing Package [Taxation](https://github.com/Harsh324/ExchangeX/tree/main/Taxation)

```py
import Taxation.taxation.taxation_functions as Tx
taxationObj = Tx.Taxation()
```
+ Taxation Package Contains
    * [taxation](https://github.com/Harsh324/ExchangeX/tree/main/Taxation/taxation) Package
---
+ This Module contains 1 Function
as mentioned in upcoming slides

---
* Function [apply_tax()](https://github.com/Harsh324/ExchangeX/blob/main/Taxation/taxation/taxation_functions.py)
+ Can be called as  ,
```py
taxationObj.apply_tax()
```
![](Img/Img11.jpg)
---

## Package [User](https://github.com/Harsh324/ExchangeX/tree/main/User)
### Hierarchy is as  shown 

```
User
├── user
│   ├──__init__.py
│   └──user_functions.py
├── tests
│   ├── __init__.py
│   └── test_functions.py
├──README.md
└──setup.py

```
---


## Importing Package [User](https://github.com/Harsh324/ExchangeX/tree/main/User)

```py
import User.user.user_functions as Ur
userObj = Ur.User()
```
+ User Package Contains
    * [user](https://github.com/Harsh324/ExchangeX/tree/main/User/user) Package
---

+ This Module contains 2 Functions 
as mentioned in upcoming slides

---

* Function [validateUser()](https://github.com/Harsh324/ExchangeX/blob/main/User/user/user_functions.py)
+ Can be called as  ,
```py
userObj.validateUser()
```
![](Img/Img12.jpg)


---

* Function [updateBalance()](https://github.com/Harsh324/ExchangeX/blob/main/User/user/user_functions.py)
+ Can be called as  ,
```py
userObj.updateBalance()
```
![](Img/Img13.jpg)


---

---


## Using the moduels
* main file for each individual module is created

* For example, Let say for Exchange module the main file is  [mainInterface.py](https://github.com/Harsh324/ExchangeX/blob/main/mainExchange.py)

* Similary for each other modules the main file is created to show the working of the module

---


## Thank You
