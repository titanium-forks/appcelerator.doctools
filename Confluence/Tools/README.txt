Command line interface client for Confluence

This is a command line interface (CLI) for remotely accessing Confluence.
This is a working command line client that can be used directly with your installation.
It uses Confluence's SOAP remote API. It also serves as an example for writing a
Java SOAP client for Confluence. This is part of a family of CLI clients supporting
Atlassian products. Also available as part of the Atlassian CLI distribution.

Installation
- Unzip the distribution package and put the enclosed directory in a convenient location
- Ensure Remote API is enabled in your Confluence installation
  -- You need to be a Confluence administrator
  -- Go to General Administration under Remote API
  -- Setting should be YES

Java Requirements
- Requires a JRE version 1.7 or higher on the client
- Run java -version from a command line
  - ensure it shows 1.7 or higher


Usage
- On a command line, cd to the directory where you installed the client
- On Windows
-- Run confluence
- On Linux, Mac, or Unix
-- Run ./confluence.sh
- On any system supporting Java
-- Run java -jar lib/confluence-cli-x.x.x.jar
- This will show help text for the command line interface client
- The client defaults to use a user of automation. Either add this user with all the authorities required to do the actions you want or specify a different user parameter
- It is recommended that you open the confluence.bat or confluence.sh file with an editor and customize it for your environment by adding server, user, and password parameters.
  Follow the example in the comments and make sure you do not remove the %* at the end of the line.

License
- This is commercially licensed software - look in the license directory for detailed license information
- The distribution ships binaries with various licenses (BSD, LGPL, and Apache)