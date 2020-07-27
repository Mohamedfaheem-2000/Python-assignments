.. code:: ipython3

    #1.Merge two sorted lists &produce one sorted list(use only one loop )
    
    list1 = [10,20,40,60,70,80]
    list2 = [5,15,25,35,45,60]
    MergedList =list1+list2
    ResSortedList=[]
    for i in range(min(MergedList),max(MergedList)+1):
         if i in MergedList:
            ResSortedList.append(i)
    print(ResSortedList)


.. parsed-literal::

    [5, 10, 15, 20, 25, 35, 40, 45, 60, 70, 80]
    

.. code:: ipython3

    #2.sort list in increasing order but all zeroes should be at right hand side.
    
    list = [0,1,2,10,4,1,0,56,2,0,1,3,0,56,0,4]
    list.sort()
    k=list.count(0);
    print(list[k:]+list[:k])
    
    


.. parsed-literal::

    [1, 1, 1, 2, 2, 3, 4, 4, 10, 56, 56, 0, 0, 0, 0, 0]
    


