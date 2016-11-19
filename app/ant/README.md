#Ant supplemental folder

Each folder's contents expose targets to a build file that imports them by

    <import file="ant/FILENAME.xml/>

It isn't necessary to explicitly declare each target or task except those specified
in their respective XML file

In other words, <target>'s can be run once <import>'ed
whereas <macrodef>'s require being declared in a target of your own choosing

To acquire the full functionality of a folder's contents, <import> the XML
file with the **ant-** prefix

##Clean
Contains tasks to "clean" (delete) everything created by any of these Ant targets

##Docs
Targets to create project documentation using JavaDocs, Java2Html, JavaNCSS, and
Checkstyle

##Init
Initializes the build process with a project.properties file and the general folder
hierarchy of the build directory to which production and test source compilation targets
can point

##Optional
Just for kicks stuff such as the banner demo from [Beginning POJOs] by Brian Sam-Bodden

##Testing
A folder whose contents attempt to establish a separation of concerns for testing with
JUnit (have the JUnit jar in your ${user.home}/.ant/lib folder)

[Beginning POJOs]:http://www.apress.com/9781590595961