# junitWorkspace

##JUnit API

The most important package in JUnit is junit.framework which contain all the core classes. Some of the important class are

Serial No	Class Name	Functionality

1	Assert	A set of assert methods.

2	TestCase	A test case defines the fixture to run multiple tests.

3	TestResult	A TestResult collects the results of executing a test case.

4	TestSuite	A TestSuite is a Composite of Tests.

##Assert Class

Following is the declaration for org.junit.Assert class:

public class Assert extends java.lang.Object

This class provides a set of assertion methods useful for writing tests. Only failed assertions are recorded.

## TestCase Class

Following is the declaration for org.junit.TestCaset class:

public abstract class TestCase extends Assert implements Test

A test case defines the fixture to run multiple tests. Some of the important methods of TestCase class are

## TestResult Class

Following is the declaration for org.junit.TestResult class:

public class TestResult extends Object

A TestResult collects the results of executing a test case. It is an instance of the Collecting Parameter pattern. The test framework distinguishes between failures and errors. A failure is anticipated and checked for with assertions. Errors are unanticipated problems like an ArrayIndexOutOfBoundsException.

##TestSuite Class

Following is the declaration for org.junit.TestSuite class:

public class TestSuite extends Object implements Test

A TestSuite is a Composite of Tests. It runs a collection of test cases.

