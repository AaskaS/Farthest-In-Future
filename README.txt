To Compile:

There are two ways to compile the file both of which are through command line
Go to the directory where the java file is located and type the following:

1. 
	javac FarthestInFuture.java
	java FarthestInFuture 1 2 3

**note, you need at least 1 argument in order for it to run & it can be any values**

2.
	java -jar FarthestInFuture.jar 1 2 3
**note, you need at least 1 argument & they can be any int values**


Test Case 1: 
1 2 3 4 5 4 5 3 2 1

Output: 
In Cache right now 1 2 3
In Cache right now 4 2 3
In Cache right now 4 5 3
In Cache right now 4 5 3
In Cache right now 4 5 3
In Cache right now 4 5 3
In Cache right now 2 5 3
Hit Count 3
Miss Count 4


Test Case 2: 
3 4 5 1 2 3 4 5 6 7 8 2 3 4 5 2 1

Output: 
In Cache right now 3 4 5
In Cache right now 3 4 1
In Cache right now 3 4 2
In Cache right now 3 4 2
In Cache right now 3 4 2
In Cache right now 3 5 2
In Cache right now 3 6 2
In Cache right now 3 7 2
In Cache right now 3 8 2
In Cache right now 3 8 2
In Cache right now 3 8 2
In Cache right now 4 8 2
In Cache right now 5 8 2
In Cache right now 5 8 2
Hit Count 5
Miss Count 9


Test Case 3:
1

Output:
Hit Count 0
Miss Count 0

