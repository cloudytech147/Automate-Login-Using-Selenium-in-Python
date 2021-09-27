# Automate Login Using Selenium in Python

OpenCV is a notable C++ library. There are, in fact, some significant level programming dialects, such as Java and Python that likewise offer help for the OpenCV library. It is an exceptionally incredible and open-source library that upholds profound learning structures to any semblance of TensorFlow, Torch, and PyTorch. 

OpenCV represents Open Source Computer Vision. Albeit for the most part utilized for ML and profound learning, there aren't numerous C++ designers who use OpenCV, paying little mind to the fact that it is locally written in C++. 

It comes with many elements that include 2,500 enhanced calculations for face recognition, object detection, object classification, 3D model extraction, picture search, and much more.

## Prerequisites for [Automating Login with Python Selenium](https://www.techgeekbuzz.com/how-to-automate-login-using-selenium-in-python/)

* Python Selenium Library

Selenium is not a standard Python library. Thus, you need to install it for your Python environment before using it. Use the following command (via the command prompt or terminal) to install the Selenium library:

```pip install selenium```

* Download Selenium Browser Driver

As Selenium will automate the login using a web browser, we require the web driver to communicate and automate the process in the web browser.

For this tutorial, we will be downloading and using the Chrome web driver because most of the developers use it. If you wish you can also download a different web driver from the list below:

* Edge web driver: https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
* Firefox web driver: https://github.com/mozilla/geckodriver/releases
* Safari web driver: https://webkit.org/blog/6900/webdriver-support-in-safari-10/

![webdrive for chrome](https://secureservercdn.net/160.153.137.163/84g.4be.myftpupload.com/wp-content/uploads/2021/01/chrome-driver.jpg)

## Automate Facebook Login with Python and Selenium

We will start coding by importing the important modules:

```#use selenium driver
from selenium import webdriver

#keys to enter input data into fields 
from selenium.webdriver.common.keys import Keys

#time module to put some delay in the process
import time
```

With the initialized driver, we can open facebook.com with the driver.get() method. This will open the website login page for us.

As we know that when we try to log into any website, we have to fill the HTML login form. Consequently, when it comes to Facebook, we have to fill the login form i.e. the email and password fields.

But when we want to automate this process with Selenium, we have to tell it which input fields should it fill. To do this, we first need to grab the input fields for email and password. We will also access the login button because once we fill the fields we need to hit it so we could log in.

The selenium driver object provides the find_element_by_name() method to access the driver page elements. Hence, we will be using this method to access the email, password, and login elements of the facebook.com page.

## Conclusion

Now you know how to use Selenium with Python to automate the login process. The only thing you need to figure out is the element name or any other attribute by which you could access the specific element in the webpage.

Apart from the find_element_by_name() method, the web driver also provides many other methods to access an element with different attributes.

