# DAY 1: Project Activity

#### Step 1: Create Repository

* Trainer has to create repository
* Add access to developer

#### Step 2: Developer Repository Access
* Developer will get invitation, Accept Invitation

#### Step 3: Clone the Repository
* git clone https://your-repo-url.git

* cd yourprojectfolder

#### Step 4: Import the Project in Eclipse

* File -> Import -> Existing Maven Project
* D:\Projects\yourprojectfolder

#### Step 5: Rename Packages

* pom.xml ( in.yourname ) => e.g: in.naresh
* Folder Structure
    * src/main/java => e.g: in.naresh
    * src/test/java => e.g: in.naresh


#### Step 6: Commit the Changes
* git add src pom.xml
* git commit -m "Renamed Folders"
* git push -u origin main


# Day 2 Project Activity

#### 1. Create Branch
* git checkout -b feature1
* Add your feature
* git status
* git add src
* git commit -m "Added Feature 1"
* git push -u origin feature1

Output:
* Pull Request URL

##### 2. Create Pull Request(PR)
* Give Pull Request - Title and Description
* Add Reviewers

##### 3. Reviewers

* Reviewers will add comments
* Reviewers will approve Pull Request 

#### 4. Merge the Code
* Click Merge Button
* Note: Feature1 branch will get merged with main branch and it will be automatically released to production.
* 



    
