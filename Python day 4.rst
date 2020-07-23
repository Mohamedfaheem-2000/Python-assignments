.. code:: ipython3

    #1.To find all the occurence of substring in given string
    str1 = "what we think we become; we are python programmer"
    substr1 = "we"
    print("The original string is : " + str1)  
    print("The substring to find : " + substr1) 
    res = [i for i in range(len(str1)) if str1.startswith(substr1, i)] 
    print("The indices of the substrings are : " + str(res)) 


.. parsed-literal::

    The original string is : what we think we become; we are python programmer
    The substring to find : we
    The indices of the substrings are : [5, 14, 25]
    

.. code:: ipython3

    #2.isupper() -Return True if the string is a uppercase string, False otherwise.
        
    string = 'FAHIM'
    print(string.isupper()) 
    string = 'FAhim'
    print(string.isupper()) 
    


.. parsed-literal::

    True
    False
    

.. code:: ipython3

    #2.islower()- Return True if the string is a lowercase string, False otherwise.
        
    string = 'fahim'
    print(string.islower()) 
    string = 'FAhim'
    print(string.islower()) 
    


.. parsed-literal::

    True
    False
    


