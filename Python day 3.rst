.. code:: ipython3

    #1.Sum of n numbers using while loop
    num=10
    sum = 0
    while(num != 0):
           sum += num
           num -= 1
    print("The sum is", sum)


.. parsed-literal::

    The sum is 55
    

.. code:: ipython3

    #2.To check whether integer is prime or not
    
    number = int(input("Enter any number: "))
    
    
    if number > 1:
        for i in range(2, number):
            if (number % i) == 0:
                print(number, "is not a prime number")
                break
        else:
            print(number, "is a prime number")
    
    
    else:
        print(number, "is not a prime number")


.. parsed-literal::

    Enter any number:  7
    

.. parsed-literal::

    7 is a prime number
    

