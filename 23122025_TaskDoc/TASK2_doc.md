# Testing the deployed CAP Application in the BTP using the POSTMAN.
### Created the application using the project accelerator (JOULE AI).
<img width="1836" height="935" alt="Screenshot 2025-12-24 110344" src="https://github.com/user-attachments/assets/a2291681-07ce-4c4d-a5dc-0d790000a1e2" />
- Added the XSUAA, MTA, HANA
- installed node modules then
- Make sure to check the hana instance running..
- Then deploy by steps build MTA (mta.yml) > deploy MTA project (right click on *.mtar file.) 

get the url from the btp cockpit > sub a/c > cloudfoundry > spaces > projects-srv > get the link.

test it in post man.

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a806df79-00b9-47dc-a85a-19422ea2ab02" />

The service ( project-srv ) is working!

testing 5000 request ping to the srv link: 
<img width="1862" height="933" alt="Screenshot 2025-12-24 120341" src="https://github.com/user-attachments/assets/70253e9e-0fb5-4e56-bc8f-006f06fd4ca4" />
