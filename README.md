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

.
    ├── configs              # Configuration files 
    │   ├── keys.js          # Load and stress tests
    │   ├── passport.js      # End-to-end, integration tests (alternatively `e2e`)
    ├── public               # Test files (alternatively `spec` or `tests`)
    │   ├── materializ.css   # Load and stress tests
    ├── routes               # Test files (alternatively `spec` or `tests`)
    │   ├── auth.js          # Load and stress tests
    │   ├── home.js          # End-to-end, integration tests (alternatively `e2e`)
    ├── views                # Test files (alternatively `spec` or `tests`)
    │   ├── dashboard.html   # Load and stress tests
    │   ├── home.html        # End-to-end, integration tests (alternatively `e2e`)
    ├── index.js
    ├── MS19802886.xml
    ├── package.json
    └── README.md

### Author
* [Dhananjaya Karandana](https://twitter.com/dkarandana)
