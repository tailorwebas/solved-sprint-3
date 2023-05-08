Download Link: https://assignmentchef.com/product/solved-sprint-3
<br>
<p class="ui header product-top-header" title="Sprint 3 Solution">One of the difficulties of writing programs as a team is that you tend to get in each other’s way. The solution to this problem is unit testing. In unit testing, whenever you write a function you also write a special test procedure that demonstrates that your new function works properly. Even though the coding takes 25% longer to write, it saves time in the long run. This is because whenever anyone in the team makes a change to the program, a quick run of unit testing framework tests that all existing functions are still running correctly.

Visual Basic has made it particularly easy to do unit testing by adding a wizard that builds the unit testing framework for you. (This has been done for you.) In the sprint this week you will add code to an existing unit test to set the input parameters for the function to be tested, and set the expected variable(s) for the value to be returned. The code is already there to compare your expected value to the actual value returned by the function being tested.

The code to load the array values for Hubs has been moved into its own function so that the unit tests will work correctly and to pave the way for next week’s sprint. If you get stuck modifying your own unit test, you may want to look at the unit test, ValueOfTest1, for inspiration, since this unit test has been completed for you. Notice that the call to the Assert.Inconclusive method has been commented out.

Story:    As a system administrator, I want a unit testing framework for easier testing and independence when writing code.

Task 1: Modify the unit test for the ValueOf function to assure that latitude is returned correctly.

Task 1a:    Right click anywhere within the ValueOf function in Airports.vb and add a unit test to the unit test framework. Rename the unit test named ValueOfTest to ValueOfTest2. (This has been done for you.)

Task 1b:    Add the line, target.LoadData(), to ValueOfTest2 immediately after the Dim statements.   Modify the code in ValueOfTest2 to assert that ID=0 andFieldName =Airports.FieldNames. Lat  Set the expected value to “33° 38′ 22″” N”.

Task 1c:    Run the unit tests to make sure they all pass.

Task 1d:    Check out the master copy of the project and install your changes.

Task 2:  Add a unit test for the ValueOf function to assure that longitude is returned correctly.

Task 2a:    Right click anywhere within the ValueOf function in Airports.vb and add a unit test to the unit test framework. Rename the unit test named ValueOfTest to ValueOfTest3. (This has been done for you.)

Task 2b:    Add the line, target.LoadData(), to  ValueOfTest3 immediately after the Dim statements.  Modify the code in ValueOfTest3 to assert that ID=0 andFieldName =Airports.FieldNames. Lon  Set the expected value to “84° 25′ 41″” W”.

Task 2c:    Run the unit tests to make sure they all pass.

Task 2d:    Check out the master copy of the project and install your changes.

Task 3:  Add a unit test for the CoordinateToDegrees function to assure that coordinates are transformed to decimal degrees correctly.

Task 3a:    Right click anywhere within the CoordinateToDegrees function in Airports.vb and add a unit test named CoordinateToDegreesTest to the unit test framework. (This has been done for you.)

Task3b:     Modify the code in CoordinateToDegreesTest to assert thatDegreeString  =  “33° 38′ 22″” N” and set the expected value to 33.63944.You will need to set delta, the third parameter of the assert.equal function, to .00001 to allow for rounding error.

Task 3c:    Run the unit tests to make sure they all pass.

Task 3d:    Check out the master copy of the project and install your changes.

Task 4:  Add a unit test for the DegreesToRadians function to assure that coordinates are transformed to radians correctly.

Task 4a:    Right click anywhere within the CoordinateToDegrees function in Airports.vb and add a unit test named DegreesToRadiansTest to the unit test framework. (This has been done for you.)

Task4b:     Modify the code in DegreesToRadiansTest to assert that DegreesDouble = 33.63944and set the expected value to 0.58712. You will need to set delta, the third parameter of the assert.equal function, to .00001 to allow for rounding error.

Task 4c:    Run the unit tests to make sure they all pass.

Task 4d:    Check out the master copy of the project and install your changes.

Task 5:  Add a unit test for the Distance function in Airports.vb to assure that a distance between two airport hubs is returned correctly.

Task 5a:    Right click anywhere within the Distance function in Airports.vb and add a unit test named DistanceTest to the unit test framework . (This has been done for you.)

Task 5b:    Add the line, target.LoadData(), to DistanceTest immediately after the Dim statements.  Modify the code in DistanceTest to assert that ID1=0 and ID2=1 returns a decimal value of 945. You will need to set delta,  the third parameter of the assert.equal function, to 1 to allow for rounding error.

Task 5c:    Run the unit tests to make sure they all pass.

Task 5d:    Check out the master copy of the project and install your changes.

Task 6: Do a final check and publish results in the Weekly Discussion Board.

Task 6a:    Run the unit tests to make sure they all pass.

Task 6b:    On Wednesday, after all team members have made their changes to the master copy, insert a copy of AirportDistances.exe in the Weekly Discussion Board for your team.