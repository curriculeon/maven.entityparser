# Entity Parser

* **Objective** - To create a `Parser` which can parse `String` and `File` to derive and return a specific object-type.
* **Purpose** - To gain familiarity with reading and parsing from Files.
* **Description** 
    * View `src.main.resources` directory to view each of the text files being read in.
    * Ensure that all test cases in `com.github.curriculeon` pass with 100% success rate. 

## Recommended Order of Completion:
### Part 0 - `FileReader`
* `FileReaser.toString()`

### Part 1 - `PersonParser`
* `PersonParser.parseString(String): Person`
* `PersonParser.parseStrings(String[]): Person[]`
* `PersonParser.parseFile(File): Person[]`

### Part 2 - `PetParser`
* `PetParser.parseString(String): Pet`
* `PetParser.parseStrings(String[]): Pet[]`
* `PetParser.parseFile(File): Pet[]`


## How to Download

#### Part 1 - Forking the Project
* To _fork_ the project, click the `Fork` button located at the top right of the project.


#### Part 2 - Navigating to _forked_ Repository
* Navigate to your github profile to find the _newly forked repository_.
* Copy the URL of the project to the clipboard.

#### Part 3 - Cloning _forked_ repository
* Clone the repository from **your account** into the `~/dev` directory.
  * if you do not have a `~/dev` directory, make one by executing the following command:
    * `mkdir ~/dev`
  * navigate to the `~/dev` directory by executing the following command:
    * `cd ~/dev`
  * clone the project by executing the following command:
    * `git clone https://github.com/MYUSERNAME/NAMEOFPROJECT`

#### Part 4 - Check Build
* Ensure that the tests run upon opening the project.
    * You should see `Tests Failed: 99 of 99 tests`







## How to Submit

#### Part 1 -  _Pushing_ local changes to remote repository
* from a _terminal_ navigate to the root directory of the _cloned_ project.
* from the root directory of the project, execute the following commands:
    * add all changes
      * `git add .`
    * commit changes to be pushed
      * `git commit -m 'I have added changes'`
    * push changes to your repository
      * `git push -u origin master`

#### Part 2 - Submitting assignment
* from the browser, navigate to the _forked_ project from **your** github account.
* click the `Pull Requests` tab.
* select `New Pull Request`
