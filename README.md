# ReHub documentation

#### Project URL is: ```https://rehub.netlify.app```
### <a href="https://rehub.netlify.app">Press here to access the project website.</a>

Our backend service is deployed on Render cloud service on free instance.
Due to low resources first time it takes longer for service
to restart (2 minutes if whole image is restarting) so please be patient.

**Registration** will be available only for people in Personal data DB.
<a href="https://github.com/7smurfs/rehub-backend/blob/master/src/main/resources/db/data/V016__Insert_personal_data.sql">Here </a>you can find all personal data. 
PIN(personal identification number) column is **OIB**, PHIN(personal health identification number) is **MBO**.
Date of birth is formated in yyyy-MM-dd. Be aware of that and that all PIIs need to be matching when user is registering.


URL for backend is: ``https://rehub-backend.onrender.com/``
If you want to spun up the backend you can press
<a href="https://rehub-backend.onrender.com/api/v1/faq">here</a> and leave that browser tab open for a while.
After that backend should be up and running.
<br>
<br>
<br>
<br>
<br>
<br>
<br>
###### Repository for UML diagrams, application documentation and project guidelines.