<h1>API Testing Project for **Inserati aici numele aplicatiei pe care o testati**</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: **JSONplaceholder.typicode**

Tools used: Postman, Newman

Collection link: **https://jsonplaceholder.typicode.com**

<h2>Tests performed</h2>

<ol>
<li>**GET all posts**</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts**<br>
Request description: **The goal of this request is to generate the list of all posts made by the users**<br>
Test types / techniques used: **Functional testing, Performance testing, Equivalence partitioning, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/33d7a171-d5d7-49a6-931e-5bac3bc4a9bb)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/faf812b2-37f1-40b7-b800-baefee1b4ff5)**<br>

<li>**GET posts by ID**</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts/2**<br>
Request description: **The goal of this request is to generate the details for a specific item, comment with ID no.2**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/acfa4e98-5684-4ea5-9947-fb27bb001a99)*<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/16efe758-1647-4350-a095-5d62bb19bf7e)**<br>

<li>**GET comment with invalid ID**</li>

HTTP method for request: **https://dummyjson.com/posts/99**<br>
Request description: **The goal of this request is to retrieve the response code 404 "Not found" when searching for a non-existent comment ID (999)**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Error message validation, Data validation**<br>
Response status code: **404 Not found**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/244e3cf5-496e-4257-841a-edf935dbc2fc)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/2ecd43a4-877e-4d57-8fe7-4fa8fc9bcaa5)**<br>

<li>**GET comment with specific Post, ID 3**</li>

HTTP method for request: **https://dummyjson.com/posts/post/3**<br>
Request description: **The goal of this request is to generate the details for a specific item, comment with ID no.3**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/e009901d-2139-4ea2-a52b-0032ebbd6899)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/16efe758-1647-4350-a095-5d62bb19bf7e)**<br>

<li>**GET count the number of posts**</li>

HTTP method for request: **https://dummyjson.com/posts**<br>
Request description: **The goal of this request is to retrieve the total number of posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/1774a107-07b0-4b1d-9940-58bb76892ea8)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/f1aec656-bb50-48e5-a958-5be9425ab821)**<br>


<li>**POST a new comment**</li>

HTTP method for request: **https://dummyjson.com/posts/add**<br>
Request description: **The goal of this request is to add a new post to the collection of posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **400 Bad request**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/a2acb249-c7b9-42bf-b64b-18f3dd1d355e)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/3e9ba5ad-c8c5-4f06-8176-10a46d02926a)**<br>

<li>**PATCH - partial update of a comment Id**</li>

HTTP method for request: **https://dummyjson.com/posts/3**<br>
Request description: **The goal of this request is to add a new post to the collection of posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/426e7bad-ac57-403b-92a6-1cd9b917ea8d)
**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/e80e2680-ece1-42c8-85c6-d91877c452bc)**<br>

<li>**PATCH - partial update of the FullName field Id 5**</li>

HTTP method for request: **https://dummyjson.com/posts/5**<br>
Request description: **The goal of this request is to update the fullName of the user Id5, which is posting the respective posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **400 Bad request**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/5356c74c-a64d-4f3a-afd1-57b9fb8f53a7)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/389db04a-e476-4eef-8b26-e8179ccb140e)**<br>

<li>**DELETE - a specific comment - no.10 **</li>

HTTP method for request: **https://dummyjson.com/posts/10**<br>
Request description: **The goal of this request is to delete comment with Id 10>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **400 Bad request**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/414476e5-2da3-4e72-9936-c4e5ded75d46)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/dfdc5895-7cad-4d5d-bab5-70bd61959d88)**<br>


Below you can find the execution report that was generated through the Postman collection runner. <br>

**![image](https://github.com/user-attachments/assets/75206cf9-08e8-4c35-ba71-ee80f5e72ed4)**<br>


The following issues were identified while running the postman tests:<br>

****Inserati aici fie un fisier pdf care sa contina raportarea tuturor bug-urilor, fie le descrieti direct in git
Bug-urile trebuie sa contina titlu, preconditii, pasi de executie, rezultate asteptate si rezultate actuale.
Optional, bug-urile pot fi raportate in jira, si apoi puteti pune poze direct din jira**

<h2>Conclusions</h2>

**Inserati aici concluziile pe care le-ati obtinut in urma executarii testelor  si introduceti informatii cum ar fi cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc**


