<h1>API Testing Project for **Inserati aici numele aplicatiei pe care o testati**</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: **DummyJSON**

Tools used: Postman, Newman

Collection link: **https://dummyjson.com**

<h2>Tests performed</h2>

<ol>
<li>**GET all comments**</li>

HTTP method for request: **https://dummyjson.com/docs/comments**<br>
Request description: **The goal of this request is to generate the list of all comments made by the users**<br>
Test types / techniques used: **Functional testing, Performance testing, Equivalence partitioning, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/33d7a171-d5d7-49a6-931e-5bac3bc4a9bb)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/cd8b37e3-48c5-4ce7-9131-28f4b29aba10)**<br>

<li>**GET comments by ID**</li>

HTTP method for request: **https://dummyjson.com/comments/3**<br>
Request description: **The goal of this request is to generate the details for a specific item, comment with ID no.3**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/e009901d-2139-4ea2-a52b-0032ebbd6899)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/16efe758-1647-4350-a095-5d62bb19bf7e)**<br>

<li>**GET comment with invalid ID**</li>

HTTP method for request: **https://dummyjson.com/comments/99**<br>
Request description: **The goal of this request is to retrieve the response code 404 "Not found" when searching for a non-existent comment ID (999)**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Error message validation, Data validation**<br>
Response status code: **404 Not found**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/244e3cf5-496e-4257-841a-edf935dbc2fc)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/2ecd43a4-877e-4d57-8fe7-4fa8fc9bcaa5)**<br>

<li>**GET comment with specific Post, ID 3**</li>

HTTP method for request: **https://dummyjson.com/comments/post/3**<br>
Request description: **The goal of this request is to generate the details for a specific item, comment with ID no.3**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/e009901d-2139-4ea2-a52b-0032ebbd6899)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/16efe758-1647-4350-a095-5d62bb19bf7e)**<br>

<li>**POST a new comment**</li>

HTTP method for request: **https://dummyjson.com/comments/add**<br>
Request description: **The goal of this request is to add a new post to the collection of comments**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **400 Bad request**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/a2acb249-c7b9-42bf-b64b-18f3dd1d355e)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/3e9ba5ad-c8c5-4f06-8176-10a46d02926a)**<br>

<li>**PATCH update a field**</li>

HTTP method for request: **https://dummyjson.com/comments/add**<br>
Request description: **The goal of this request is to add a new post to the collection of comments**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/426e7bad-ac57-403b-92a6-1cd9b917ea8d)
**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/e80e2680-ece1-42c8-85c6-d91877c452bc)**<br>

.............

<li>**Nume Request n**</li>

HTTP method for request: **Inserati aici metoda HTTP a requestului**<br>
Request description: **Inserati o scurta descriere a requestului, conform documentatiei de API**<br>
Test types / techniques used: **Inserati tipurile si tehnicile de testare folosite pentru acest request**<br>
Response status code: **Inserati aici status code-ul pe care l-ati obtinut in urma executiei requestului**<br>

Below you can find a picture of the API request from Postman:<br>

**Inserati aici o poza cu requestul din postman in care sa se observe request method, endpoint, request body si response body**<br>

JavaScript Tests:

**Inserati aici o poza cu testele in java script pe care le-ati definit impreuna cu rezultatele executiei acestora**<br>

</ol>

<h2>Execution report for the created API collection </h2>

Below you can find the execution report that was generated through the Postman collection runner. <br>

**Inserati aici o poza cu raportul de executie din Postman**<br>

The collection was also run through newman directly from the terminal, and the results can be found below:<br>

**Inserati aici o poza cu raportul de executie din Newman**<br>

<h2>Defects found</h2>

The following issues were identified while running the postman tests:<br>

****Inserati aici fie un fisier pdf care sa contina raportarea tuturor bug-urilor, fie le descrieti direct in git
Bug-urile trebuie sa contina titlu, preconditii, pasi de executie, rezultate asteptate si rezultate actuale.
Optional, bug-urile pot fi raportate in jira, si apoi puteti pune poze direct din jira**

<h2>Conclusions</h2>

**Inserati aici concluziile pe care le-ati obtinut in urma executarii testelor  si introduceti informatii cum ar fi cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc**


