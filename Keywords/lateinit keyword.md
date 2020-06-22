# lateinit keyword

- use it with mutable variables [var].
- allowed with only non-nullable datatypes.
- It is a promise to compiler that the value will be initialised in future.
- if you try to access the **lateinit** variable without initialising it then it throws **UninitialisedPropertyAccessException**.
