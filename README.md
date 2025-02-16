# bug-reports
Câteva bug report-uri ce depistează probleme din diferite site-uri
## 1. No currency in product cart
### Description
Currency is shown on product prices in areas except the product cart.
### Steps to reproduce
1. Visit https://www.demoblaze.com
2. Add a product to the cart
3. Click on "Cart"
### Expected result
User sees the dollar ($) currency on the item price.
### Actual result
Currency is not visible on the item price.<br/>

![Screenshot 2025-02-12 155357](https://github.com/user-attachments/assets/3edbe193-a4a6-41a6-b753-7f73d3fb0f0a)
![Screenshot 2025-02-12 155540](https://github.com/user-attachments/assets/2a22cb46-4afe-46d0-8cef-d129b0e33583)
## 2. Account numbers shown as joint string
### Description
Each pre-made customer has 3 bank account numbers that are not semantically separated (e.g. a comma).
### Steps to reproduce
1. Visit https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Click on "Bank Manager Login"
3. Click on "Customers"
### Expected result
Each bank account number is shown separately.
### Actual result
No separation is present between account numbers.<br/>

![Screenshot 2025-02-12 160800](https://github.com/user-attachments/assets/ef4d5ac2-2206-4fbd-a2d4-156b689696d0)
## 3. Maximum value mistaken for excess
### Description
The maximum intake values are interpreted as having passed the consumption limit.
### Steps to reproduce
1. Visit https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator
2. Increase the number of coffee cups and cigarettes until a warning is given
3. Modify the milligram values to the given maximum limit
### Expected result
The maximum intake limit is not exceeded, and no warning is given.
### Actual result
User is warned that they have exceeded the limit.<br/>

![Screenshot 2025-02-12 161520](https://github.com/user-attachments/assets/601469f6-a556-4e23-a45d-15bf075379b9)
## 4. Website resources errors
### Description
Resources from the Primăria Techirghiol website failed to load.
### Steps to reproduce
1. Visit https://www.primariatechirghiol.ro
2. Press F12 to open DevTools
3. Click on the "Console" tab/icon
### Expected result
All background resources load successfully.
### Actual result
Some of these resources return errors.<br/>

![Screenshot 2025-02-12 162016](https://github.com/user-attachments/assets/ef5d1e91-69df-42e7-a4b7-7535f8b71b28)
## 5. Wrong grammar usage
### Description
The link and button of the lower-right cookie pop-up use incorrect grammar.
### Steps to reproduce
1. Visit https://juice-shop.herokuapp.com/#/login
2. Notice any grammar mistakes in the cookie pop-up
### Expected result
Correct grammar is used throughout the pop-up.
### Actual result
The link and button do not use proper grammar.<br/>

![Screenshot 2025-02-16 102130](https://github.com/user-attachments/assets/58923d72-e6ce-49c1-8fbf-3989e941c1e5)
## 6. Website presentation problem
### Description
The presentation indicated by the Fieni website is not shown upon pressing the play button.
### Steps to reproduce
1. Visit https://fieni.ro
2. Scroll down until you see "Clip de prezentare al Orașului Fieni"
3. Click the play button
### Expected result
The button takes the user to the city presentation.
### Actual result
The play button does not work.<br/>

![Screenshot 2025-02-16 102856](https://github.com/user-attachments/assets/958b7138-e98e-4d3e-901b-cd989bee4a18)
## 7. Missing third challenge
### Description
Users can mistake the number of challenges due to a missing third challenge.
### Steps to reproduce
1. Visit http://testingchallenges.thetestingmap.org/index.php
2. See the left menu for available challenges
### Expected result
User has 11 challenges to complete.
### Actual result
User has only 10 challenges due to a missing third challenge.<br/>

![Screenshot 2025-02-16 103258](https://github.com/user-attachments/assets/65e1801d-a632-4692-bea6-d36b7c6d3793)
