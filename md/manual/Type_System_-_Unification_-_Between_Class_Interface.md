When defining unification behavior between classes, it is important to remember that unification is directional: We can assign a more specialized class (e.g. a child class) to a generic class (e.g. a base class), but the reverse is not valid.

The following assignments are allowed:



* child class to base class
* class to implementing interface
* interface to base interface


These rules are transitive, meaning that a child class can also be assigned to the base class of its base class, an interface its base class implements, the base interface of an implementing interface and so on.