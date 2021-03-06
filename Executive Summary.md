#Executive Summary<br>
##Problem Statement<br>
Developers in organizations or companies are frequently using the external source code for better cost efficiency and time efficiency,
but there are many potential risks when developers add external code to their programs. The problem is how to create a system that can help
developers avoid risks while still receive benefits from open source software. One of the main issues is external source code has not yet
been tested license and vulnerability by FOSSOLOGY Scanner and NIST Vulnerability Database. The project manager cannot decide whether the
external code fits organization policy or not.<br>

##Solution<br>
The solution to this problem is to have a process that sends external package to check package license and vulnerability information
FOSSOLOGY Scanner can check packages licenses availability for developers and then store the result to the organization license and vulnerability database.
NIST Vulnerability Database is a perfect place for checking package vulnerability information, so all of the package vulnerability results
can be stored in the organization's license and vulnerability database. The manager can take the package license and vulnerability result
and check with the policy database to determine whether the package is usable in the project situation. Also, the manager has the authority to edit and create policies to the policy database, so the organization can better manipulate with external packages.<br>
