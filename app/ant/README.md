#Ant supplemental folder

## Notes
Each folder's contents expose targets to a build file that imports them by

````xml
<import file="ant/FILENAME.xml/>
````

It isn't necessary to explicitly declare each target or task except those specified in their respective XML file.

In other words, target's can be run once imported whereas macrodefs require being declared in a target of your own choosing.

To acquire the full functionality of a folder's contents in a single import, import the XML file with the **ant-** prefix

## clean
Contains tasks to "clean" (delete) everything created by any of these Ant targets.

## docs
Targets to create project documentation using JavaDocs, Java2Html, JavaNCSS, and Checkstyle.

## init
Initializes the build process with a project.properties file and the general folder hierarchy of the build directory to which production and test source compilation targets can point.

## optional
Just for kicks stuff such as the banner demo from [Beginning POJOs](http://www.apress.com/9781590595961) by Brian Sam-Bodden.

## testing
A folder whose contents attempt to establish a separation of concerns for testing with JUnit (a little old school, but this example assumes I have the JUnit jar in ${user.home}/.ant/lib folder)