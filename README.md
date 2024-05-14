# customer-data-migration

### install dependencies

`npm i`

# Migration

### migrate auth-email

`node index.js --migrate auth-email --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate port

`node index.js --migrate port --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate identity

`node index.js --migrate identity --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate accounts

`node index.js --migrate accounts --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate ever_approved

`node index.js --migrate ever-approved --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate banks

`node index.js --migrate banks --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate open_account_at

`node index.js --migrate open-account-at --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate plans

`node index.js --migrate plans --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate advisor

`node index.js --migrate advisor --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`

### migrate remove-subscriber

`node index.js --migrate remove-subscriber --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI>`

### migrate open_account_state

`node index.js --migrate open-account-state --db <MONGO_DB> --collection <MONGO_COLLECTION> --uri <MONGO_URI> --path <PATH_TO_CSV>`
