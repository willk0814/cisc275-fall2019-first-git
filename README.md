# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
Main creates 3 dog objects and 2 animal objects to be used for comparison
3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?
The comparator constructor call is: Collections.sort(dogs, new Comparator<Animal>()
The class definition for the comparator is: public int compare(Animal a, Animal b){
			    return a.getLegs() - b.getLegs();
