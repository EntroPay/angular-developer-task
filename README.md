# Angular Developer Task

The assignment requires the development of a small application to manage a set of bank cards which a user owns. We will be only assessing the design and implementation of the app provided the following terms are also met:
- Angular 2 or 4.x is used
- WebPack is optional, but preferable as a solution to transform and bundle the written code
- TypeScript is optional, but preferable
- A small set of unit tests to compliment the implementation below.

### Model
For the purpose of this task, the following two models will be required:
- An `Account`, bearing the following fields:
  - username
  - password
  - full name
- A `Card`, bearing the following fields:
  - card name
  - card number
  - expiry date
  
An `Account` may own multiple `Card` instances in the app. `Card` instances should have a unique `card name`.

Any means of storage and data management is accepted (we recommend Local Storage as the easiest solution).

###Landing Page
This will be the first page that the user will be visiting, and must have the following features:
- Allow users to register an account.
- Sign into the account using standard username-password credentials.
- Sign out of the account.

###Dashboard Page
This is the page that the user should see after registration/sign-in, and should have the following functionality:
- create a card and bind it to the account
- show all the card and their details which that account currently owns
- delete a card
- update the card alias, and expiry date

###Decorator
The application should have a footer that is common to all protected and unprotected pages, and a header that is common to all protected pages, exposing navigation between pages and account logout.

###Some other conditions and tips
- **Important!** The app should forbid users to access _protected pages_ unless the user is authenticated. 
- Do not bother styling the pages for the sake of aesthetics! Functionality and technical design is what we are after.

_Questions? Feel free to reach us at job@entropay.com and we will do our best to reply as soon as possible._
