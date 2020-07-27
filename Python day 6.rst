.. code:: ipython3

    #1.To convert a list into dictionary using dictionary comprehension
    
    list1=[1,2,3,4,5]
    list2=["a","b","c","c","e"] 
    res = {list1[i]: list2[i] for i in range(len(list1))}   
    print ("Resultant dictionary is : " +  str(res)) 


.. parsed-literal::

    Resultant dictionary is : {1: 'a', 2: 'b', 3: 'c', 4: 'c', 5: 'e'}
    

