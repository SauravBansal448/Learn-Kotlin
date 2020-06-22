# "lazy" keyword

- **lazy initialisation** was designed to prevent unnecesary initialization of objects.
- Your variables will not be initialised unless you use it in your code.
- It is initialised only once.
- Next time when you use it, you get the value from cache memory.

- It is thread safe which means It is initialised in the thread where it is used for the first time.
    - if you use lazy variable in other thread then you can get the value from the cache memory.
    
- It could be use with **var** and **val** both.
- The variable can be **nullable** or **non-nullable**
