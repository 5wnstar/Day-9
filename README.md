# Day-9
30 Days of codding

Submitting web forms


During web browsing, we submit web forms many times in a day. Now, you would like do that using the Python code.
Getting ready
This recipe uses a third-party Python module called requests. You can install the compatible 
version of this module by following the instructions from http://docs.pythonrequests.org/en/latest/user/install/. For example, you can use pip to install 
requests from the command line as follows:
$ pip install requests




Let us submit some fake data to register with www.twitter.com. Each form submission 
has two methods: GET and POST. The less sensitive data, for example, search queries, are 
usually submitted by GET and the more sensitive data is sent via the POST method. Let us 
try submitting data with both of them.



