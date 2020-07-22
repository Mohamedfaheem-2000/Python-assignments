.. code:: ipython3

    #backslash
    print("Python world")


.. parsed-literal::

    Python world
    

.. code:: ipython3

    print('Python\'s world')


.. parsed-literal::

    Python's world
    

.. code:: ipython3

    print(""""Python   
          world""") #triple quotes


.. parsed-literal::

    "Python 
          world
    

.. code:: ipython3

    print("Python\
           world")


.. parsed-literal::

    Python       world
    

.. code:: ipython3

    print("Python\nworld")   #newline


.. parsed-literal::

    Python
    world
    

.. code:: ipython3

    print("Python \t world")     #tab


.. parsed-literal::

    Python 	 world
    

.. code:: ipython3

    print("Python \a world")


.. parsed-literal::

    Python  world
    

.. code:: ipython3

    name="fahim"
    age=20
    mark=75
    print("The name is",name,"age is",age,"marks scored",mark)    #formatted output


.. parsed-literal::

    The name is fahim age is 20 marks scored 75
    

.. code:: ipython3

    print("The name is %s age is %d marks scored %d"%(name,age,mark))    #formatted output


.. parsed-literal::

    The name is fahim age is 20 marks scored 75
    

.. code:: ipython3

    x=10
    id(x)




.. parsed-literal::

    140727906509488



.. code:: ipython3

    y=10
    id(y)




.. parsed-literal::

    140727906509488



.. code:: ipython3

    #arithmetic operators
    5**5




.. parsed-literal::

    3125



.. code:: ipython3

    5*2




.. parsed-literal::

    10



.. code:: ipython3

    5+2




.. parsed-literal::

    7



.. code:: ipython3

    5-2




.. parsed-literal::

    3



.. code:: ipython3

    5/2




.. parsed-literal::

    2.5



.. code:: ipython3

    5//2




.. parsed-literal::

    2



.. code:: ipython3

    #comparison operator
    a=5
    b=10
    a==b




.. parsed-literal::

    False



.. code:: ipython3

    a<b




.. parsed-literal::

    True



.. code:: ipython3

    a>b




.. parsed-literal::

    False



.. code:: ipython3

    a!=b




.. parsed-literal::

    True



.. code:: ipython3

    a>=b




.. parsed-literal::

    False



.. code:: ipython3

    #assignment operators
    a+=b
    print("The value of a is",a)


.. parsed-literal::

    The value of a is 35
    

.. code:: ipython3

    a-=b
    print("The value of a is",a)


.. parsed-literal::

    The value of a is 25
    

.. code:: ipython3

    a*=b
    print("The value of a is",a)


.. parsed-literal::

    The value of a is 250
    

.. code:: ipython3

    a/=b
    print("The value of a is",a)


.. parsed-literal::

    The value of a is 25.0
    

.. code:: ipython3

    #bitwise
    a=2
    bin(a)
    




.. parsed-literal::

    '0b10'



.. code:: ipython3

    b=5
    bin(b)




.. parsed-literal::

    '0b101'



.. code:: ipython3

    a|b




.. parsed-literal::

    7



.. code:: ipython3

    a&b




.. parsed-literal::

    0



.. code:: ipython3

    #membership
    a="hello"
    "e" in a
    




.. parsed-literal::

    True



.. code:: ipython3

    a="hello"
    "f" not in a




.. parsed-literal::

    True



.. code:: ipython3

    #identity
    a=1.6
    b=1.6
    a is b




.. parsed-literal::

    False



.. code:: ipython3

    #precedence
    10*5/2-8




.. parsed-literal::

    17.0



.. code:: ipython3

    2+88*10
    




.. parsed-literal::

    882



.. code:: ipython3

    2**-1




.. parsed-literal::

    0.5



