Using the Object.clone() method creates a clone of the object. This is a shallow copy, so the object itself is cloned, but not the objects it refers to. For example, if you clone a list, the list is cloned, but the elements in the list are not cloned. 

The close will work for primitive types, but not for objects. If you want to clone an object, you need to use the clone() method of the object - each of the objects if you are in a list.

**Need to Review:** An easy rule of the thumb is whether the object is mutable or immutable. If the object is mutable, you need to clone it. If the object is immutable, when the object is cloned and then updated, the original object is not updated and new object is created. 
This means we can update the objects in the list without modifying any of the held objects. Lists only deal with references to objects, so if you update the object, the list will reflect the change. 
 
