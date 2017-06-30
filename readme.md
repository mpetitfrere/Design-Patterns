Data Patterns Singleton
  A singleton is a class that is instantiated only once. This is typically accomplished by creating a static field in the class representing the class.
  A static method exists on the class to obtain the instance of the class and is typically named something such as getInstance(). 
  The creation of the object referenced by the static field can be done either when the class is initialized or the first time that getInstance() is called. 
  The singleton class typically has a private constructor to prevent the singleton class from being instantiated via a constructor. 
  Rather, the instance of the singleton is obtained via the static getInstance() method. 
