# MapReduce

This application is developed to demonstrate Word count application using MapReduce Programming Paradigm.

MapReduce Programming Paradigm involves 
	1. Map phase
	2. Reduce phase
	
Below are the three classes that are developed for word count application.

1. TokenizerMapper.java:
	Created TokenizerMapper class extending base Mapper class and implemented custom business logic for 
	Mapper Class. 
	
2. IntSumReducer.java:
	Developed IntSumReducer class extending base Reducer class and implemented custom business logic for 
	Reducer class.
	
3. WordCount.java:
	Developed WordCount class which functions as driver class for creating and submitting MapReduce job.
