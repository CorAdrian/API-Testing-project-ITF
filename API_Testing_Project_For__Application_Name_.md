<h1>API Testing Project for **Inserati aici numele aplicatiei pe care o testati**</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: **JSONplaceholder.typicode**

Tools used: Postman

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

HTTP method for request: **https://jsonplaceholder.typicode.com/posts/101**<br>
Request description: **The goal of this request is to retrieve the response code 404 "Not found" when searching for a non-existent comment ID (999)**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Error message validation, Data validation**<br>
Response status code: **404 Not found**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/2586a6f9-cac6-4917-b2c1-66b4177aba50)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/3001b6a8-f52c-4453-ad97-18baa581363a)**<br>

<li>**GET comment with specific Post, ID 3**</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts/3**<br>
Request description: **The goal of this request is to generate the details for a specific item, comment with ID no.3**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/4c83de5a-0523-4a68-a3af-d5e939b46664)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/b5604e7f-1257-41e0-b1a3-41530280b978)**<br>

<li>**GET count the number of posts**</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts**<br>
Request description: **The goal of this request is to retrieve the total number of posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Boundary Value Analysis, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/41317634-1079-49de-ba88-e14e5ebc3c8f)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/6470cceb-be91-419a-90c4-185d9dc912d4)**<br>


<li>**Add a new post**</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts/add**<br>
Request description: **The goal of this request is to add a new post to the collection of posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **201 created**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/2c03d674-64e1-44a9-9324-3e7d2d7560dd)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/32cb0d44-6890-4451-bc06-ee7b4c1410b8)**<br>


<li>**PUT - update of a post**</li>

HTTP method for request: **https://dummyjson.com/posts/3**<br>
Request description: **The goal of this request is to add a new post to the collection of posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/adadfaed-a4c4-488d-8637-d83e7241e646)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/66805378-1ae0-463e-b475-07a410b6073f)**<br>


**<li>**PATCH - partial update of a comment Id**</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts/7**<br>
Request description: **The goal of this request is to update partially, specific fields of a post**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/bc7dda9c-4baa-44e4-a049-455c9a39dcd4)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/d453459e-d53d-4466-92fd-848dfc269c23)**<br>

<li>**PATCH - partial update of the FullName field Id 3**</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts/3**<br>
Request description: **The goal of this request is to update the fullName of the user Id5, which is posting the respective posts**<br>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **400 Bad request**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/0dbc0638-04b3-4566-b6e9-5c9896f75c46)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/3a36c64e-d808-4888-bf10-c42fb6efde3b)**<br>

<li>**DELETE - a specific comment - no.101 **</li>

HTTP method for request: **https://jsonplaceholder.typicode.com/posts/101**<br>
Request description: **The goal of this request is to delete comment with Id 10>
Test types / techniques used: **Functional testing, Performance testing, Data validation**<br>
Response status code: **400 Bad request**<br>

Below you can find a picture of the API request from Postman:<br>

**![image](https://github.com/user-attachments/assets/414476e5-2da3-4e72-9936-c4e5ded75d46)**<br>

JavaScript Tests:

**![image](https://github.com/user-attachments/assets/24accbbc-2115-4b86-a39e-23438b2cf5d1)**<br>


Below you can find the execution report that was generated through the Postman collection runner. <br>

**![image](https://github.com/user-attachments/assets/75206cf9-08e8-4c35-ba71-ee80f5e72ed4)**<br>


The following issues were identified while running the postman tests:<br>

**NR.
Cerinta
Rezultat asteptat
Rezultat returnat
Pasi pentru remediere
1
Request GET
Sa genereze mesaj de eroare pentru non-valid post id
404 Not found
-Deschidere tool Postman 
- Se updateaza scriptul pentru a returna rezultatul necesar
2
Request GET
Sa genereze cod de validare 200 OK.
Codul generat este 404 Not found.
-Deschidere tool Postman 
- Se updateaza scriptul pentru a returna rezultatul necesar
3
Request GET
Sa confirme campurile existente, cand se solicita status, sa genereze in body field - ‘status ok’
In body field nu s-a generat niciun raspuns.
-Deschidere tool Postman 
- Se updateaza scriptul pentru a returna rezultatul necesar**

<h2>Conclusions</h2>

**Prezentul proiect a fost intocmit pentru testarea API a aplicatiei jsonplaceholder, pentru administrarea requesturilor si pentru efectuarea testelor, precum si pentru rularea raportului de executie.
Defectele identificate semnifica probleme importante in administrarea colectiei de date API si poate avea ca impact inregistrarea unor date incorecte sau incomplete in baza de date. Codurile de eroare generate si inregistrarea de date inconsistente pot creea confuzie in cadrul utilizatorilor, putand duce la posibile nemultumiri, feed back negativ si probleme de reputatie.
Corectarea defectelor identificate este deci o masura urgenta si obligatorie, inainte de lansarea tool-ului.**


