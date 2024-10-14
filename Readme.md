
Aplicație web pentru conservarea alimentelor și reducerea risipei
Aceasta este o arhitectură pe 3 niveluri, cu frontend-ul realizat în Angular, backend-ul în Node.js (Express.js) și REST APIs, folosind framework-ul Sequelize ORM și baza de date MySQL.

Simte-te liber să pui orice întrebare.

Descarcă Node.js (dacă nu este instalat)
https://nodejs.org/en

Instalează Angular CLI (dacă nu este instalat)
diff
Copy code
npm install -g @angular/cli
Adaugă Angular Material (dacă nu este instalat)
diff
Copy code
ng add @angular/material
Pachete NPM care trebuie instalate în proiectul frontend Angular:
diff
Copy code
npm install --save ngx-shimmering-loader
npm i @auth0/angular-jwt
npm install sweetalert2
npm i ngx-image-cropper
npm i ngx-file-drag-drop
npm i ngx-image-compress
npm i ng-lazyload-image
npm i ngx-countdown
npm install card-validator
npm i ngx-star-rating
npm i ng-image-slider
npm install --save ngx-webcam
npm i -s @angular/flex-layout @angular/cdk
Pachete NPM care trebuie instalate în proiectul backend:
diff
Copy code
npm init
npm install express sequelize mysql2 cors
Baza de date
Importă baza de date furnizată în SQLyog.

Demo:
1. Înregistrare pe site


![Responsive register page](https://user-images.githubusercontent.com/77499979/227800030-80f2f36c-0907-4143-be94-6fef6f10c346.jpeg)
2. Sau autentifică-te dacă ești deja înregistrat
![Login required](https://user-images.githubusercontent.com/77499979/227800100-23a80b4b-7595-41b8-bdac-e1ed5abbeafd.jpeg)

3. Adaugă un articol nou


![add new auction](https://user-images.githubusercontent.com/77499979/227800173-f6b57be8-96e8-487c-bb38-1c4a57ce473c.jpeg)

4. Pagina principală pentru listarea aplicațiilor
![Homepage](https://user-images.githubusercontent.com/77499979/227800345-647484b8-dd43-4969-80b4-9d248555550c.jpeg)

5. Licitatorii pot vedea și plasa oferte. Cumpărătorii/licitatorii pot vedea ofertele altora.
5.1 Detaliile licitației văzute de licitator
![Bid details](https://user-images.githubusercontent.com/77499979/227800402-44a95f85-ef71-409f-a2f3-380ac6fbce4b.jpeg)

5.2 Licitatorul plasează o ofertă


![Bid details update](https://user-images.githubusercontent.com/77499979/227800440-6e77abc1-e622-4f56-a737-0ff47aafbe50.jpeg)
6. Profilul licitatorului arată istoricul de vânzări și licitații

![profile](https://user-images.githubusercontent.com/77499979/227800581-1c14a505-a514-42e7-9fa9-ca4128dc07ea.jpeg)
Alți licitatori pot vedea ofertele fără să se înregistreze, dar nu pot plasa oferte fără autentificare.

![image](https://user-images.githubusercontent.com/77499979/227801000-317bfa90-3e15-4d4a-b580-ee95fb3f917b.png)
7. Vânzătorul aprobă oricare dintre oferte

![image](https://user-images.githubusercontent.com/77499979/227801041-73d46ce8-b12d-4f26-9c33-4ab403c6e709.png)
8. Licitatorii sunt informați dacă oferta lor a fost aprobată sau nu

![image](https://user-images.githubusercontent.com/77499979/227801126-e2245e0e-27ca-4c23-8d23-37969cbe82bd.png)
9. După aprobare, licitatorul va plăti suma ofertei plasate

![image](https://user-images.githubusercontent.com/77499979/227801188-d52f388e-ec0b-4366-87fc-a8c21bb81746.png)
10. Vânzătorii vor fi informați despre plata primită

![image](https://user-images.githubusercontent.com/77499979/227801586-1d489015-bb9d-4b78-bcf7-4e5256c31331.png)
Panou de Admin
![image](https://user-images.githubusercontent.com/77499979/227801263-b6a6e591-facb-4630-9f48-bfb8346a40ea.png)

Aplică unele filtre:

![image](https://user-images.githubusercontent.com/77499979/227801301-23f2aca7-d0a6-4d51-b6b8-412cd869be90.png)














