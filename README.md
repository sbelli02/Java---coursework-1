1- Description of the work

1.1Knapsack

In this coursework, we want to write a class Knapsack. Its instances can store and provide information about objects of a class Item . The Items stored in our Knapsack objects are very simple: they have a name and a weight. A Knapsack object can then tell us, e.g., the average weight of its current items, the number of current items, etc .The following example:
Knapsack sack = new Knapsack();
sack.add(new Item("Soda", 400));
sack.add(new Item("Book", 100));
System.out.println(sack.numberOfItems());
sack.add(new Item("Pen", 15));
System.out.println(sack.numberOfItems());
should print:
 2
3
Here, the method numberOfItems() returns the number of items that have been added to the knapsack so far. When we called sack.numberOfItems() for the first time, only the first two items, named "Soda" and "Book", had been added to our knapsack, so the result was 2. When we then called sack.numberOfItems() for the second time, the third item, named "Pen", had also been added to our knapsack, so the result was 3. Thus, the same method call on the same knapsack object (e.g. sack.numberOfItems()) can have different results, depending on the state of the object. In this coursework we do not want to analyse any null item references.

2.Coursework1Main 

This class makes use of some of the desired functionalities of the class Knapsack in the main method. You can test your implementation of Knapsack by running Coursework1Main.main. These tests provide further clarification for the behaviour that Knapsack is supposed to show. 


