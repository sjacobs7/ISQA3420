# Open Source Software (OSS) Policy System
# DFD Dictionary
___

## *Entities*

#### Developer

The developer initially populates the license and vulnerability database. The developer can also query the license and vulnerability database.

#### Manager

The manager queries the license an vulnerability database, and creates or modifies policies surrounding the usage of the software package.
---

## *Processes*

#### Scan Software for Licenses & Vulnerabilities

Vulnerability data is gathered from the NIST database. License data is gathered from Fossolgy by uploading the software package.

#### Request License and Vulnerabily Data

License and Vulnerability data is returned to either the manager or developer after a request has been made.

#### Update or Read Policy Data

The manager can add new policy or modify existing policy in the Policy Database
---

## *Data Flows*

#### Software Package

The software package is the entire package itself, usually in a .zip or tar.gz file and containing all files for actual progarm execution. 

#### Software Package Name

The software package name is simply passed to the NIST database for gathering vulnerabilty data.

#### Vulnerability Data

Vulnerability data is the resultant data from passing the software package name to the NIST database.

#### License Data

License data is the resultant data from uploading the Software Package to the Fossology server.

#### License and Vulnerability Query

A query made by entities who wish to obtain the the license and vulnerability data for a particular software package.

#### License and Vulnerability Results

The results returned to an entity's License and Vulnerability Query

#### Policy Data Request

A request to either create, modify, or retrieve a policy surrounding the usage of a software package.

#### Policy Data Response

The resultant outcome of creating, updating, or retrieving a policy.
