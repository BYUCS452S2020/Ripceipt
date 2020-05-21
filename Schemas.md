# Database Schemas

#### User

user (<ins>user_id</ins>, username, password, salt, first_name, last_name, email)

Contains user information for login

#### Receipt

receipt (<ins>receipt_id</ins>, store_id, user_id)

Contains receipt information
* Foreign keys store_id and user_id reference the receipt issuer and receiver, respectively, entries in the store and user tables

#### Store

store (<ins>store_id</ins>, store_name, manager, location, external_store_id)

Contains store information
