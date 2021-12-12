# SQMA_Andreea_Bodea
Simple example of Java class with JUnitTests
# Compilation
javac Calculation.java
javac -cp .;./junit-4.13.2.jar;./hamcrest-core-1.3.jar TestLogic.java
javac -cp .;./junit-4.13.2.jar;./hamcrest-core-1.3.jar TestCase2.java
java -cp .;./junit-4.13.2.jar;./hamcrest-core-1.3.jar org.junit.runner.JUnitCore TestLogic
java -cp .;./junit-4.13.2.jar;./hamcrest-core-1.3.jar org.junit.runner.JUnitCore TestCase2
