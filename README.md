# URL hit counter

### Requirement
* IntelliJIDEA
* Serverport: 8080 (use: localhost:8080)
* Java version: 17
* Everything is present in the pom.xml (no need to download any library)

## Steps to run visitCounter Project
* Download the source code and import in intellijIDEA.
* Go to localhost:8080/
* End point:api/v1/visitor-count-app/username/{username}/count
### In this counter feature there is -
* count, variable to count url hits
* User, It defies who has visited the server and how many times they has visited
* HashMap, it stores the usernames and their counts
