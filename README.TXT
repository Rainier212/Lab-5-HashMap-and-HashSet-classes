TechSupport - the DodgySoft Technical support system.

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

This project is discussed in chapter 6.


This project implements a technical support system for customers of the 
DodgySoft software company. Users can describe their software problems and 
get advice instantly!

The idea is based on Eliza - a famous program described by Joseph Weizenbaum 
in 1966. (Do a web search for "Eliza" and "Weizenbaum" if you want to know 
more about this.)

In fact, it is much more primitive than Eliza. But that's enough to match the 
quality of many software companies' technical support advice...  ;-)

To start this program, create a SupportSystem object and execute the "start" 
method.

Then start describing your problem by typing in the terminal window.

The purpose of this project is to demonstrate and study library classes, such 
as ArrayList, HashMap, HashSet, and Random.

ANSWERS TO QUESTIONS:

24. A HashgMap stores items in key/value pairs, where each key maps to a specific value.To use it, we have to create a HashMap object, then add items to it.
*Source - https://www.w3schools.com/java/java_hashmap.asp*

25. containsKey(Object key)
    keySet()
    remove(Object key)
    get(Object key)
    put(K key, V value)

26. You can check how many entries are in a map by calling the size() method.

28. It replaces the old value with the new one you entered. For example, if it was 15, and I entered 16 for the next one, it would return 16 instead of the original, 15.

29. Both of their values are stored in the map.

30. map.containsKey(Object key)

31. It will return null

32. for (String key : map.keySet()) {
  	System.out.println(key);
    }

33. I wasn't able to do this step because I didn't understand what and how to do it. :(

34. Both of them stores a collection of items. However, ArrayList allows duplicate elements, while HashSet does not. ArrayList also maintains the inserstion order, but the order for a HashSet is not guaranteed.

35. The HashSet will return words in no particular order and without any duplicates. The ArrayList will follow the insertion order and allow duplicates.

36. I don't think there would be a problem.

37. For question 37, the code was already there. Therefore I didn't have to add anything.


**For the Challenge exercises in this part, I do not understand what to do, and how to do them ( I was absent during the lab, so I wasn't able to ask questions about these exercises. I would ask, but the time I am doing this work, it is pretty late at night.). Sorry!**
