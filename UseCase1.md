# Use Case
___

* **Title**: Upload license and vulnerability information to the License and Vulnerability Database.

* **Primary Actor**: Developer

* **Goal in Context**:  The developer is able to find the licenses and vulnerabilities for a specific software package and upload that information to the database. 

* **Stakeholders**: 
    - Developer: To upload pertinent and meaningful information to the database.

* **Preconditions**:
    - The software package is available to be scanned for licenses.
    - A tool to scan the package for licenses is available.
    - A stable internet connection is available to search for vulnerabilities.
    - The NIST database is available to send the software package name to.
    - A database has been created to store the information. 

* **Main Success Scenario**: License and vulnerability data is successfully uploaded and stored in the database.

* **Failed End Conditions**: License and vulnerability data is not recorded or unsucessfully stored in the database.

* **Trigger**: A software package is considered for use in a project and needs to be evaluated for licenses and vulnerabilities.
