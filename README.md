# GoogleDrive OATH2.0 APP

## Installation

### Package Manager, [npm](https://www.npmjs.com)

```bash
$ npm install
```

### Developmnet Environment

```bash
$ npm run dev
# Development stage ( This will nodemon internally ).

$ npm run prod
# Production version ( This command will run node index.js internally to perform well in production environment ).

```

### Folder Structure
```
.
    ├── configs              # Configuration files 
    │   ├── keys.js          
    │   ├── passport.js      
    ├── public               # FrontEnd Libraries
    │   ├── materializ.css   # materializ lib
    ├── routes               # Page routes
    │   ├── auth.js          
    │   ├── home.js          
    ├── views                # Views
    │   ├── dashboard.html   
    │   ├── home.html       
    ├── index.js
    ├── MS19802886.xml       # submission details
    ├── package.json
    └── README.md
```
### Author
* [Dhananjaya Karandana](https://twitter.com/dkarandana)
