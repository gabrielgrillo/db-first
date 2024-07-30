# DB LIBRARY

table: books

- id PK AI UNIQUE BIGINT
- title VARCHAR (80) NOTNULL
- author VARCHAR(255) NOTNULL
- genre_id FR
- available_copies INT 
- condition_id FR

table: members
- id PK AI UNIQUE BIGINT

table: loans
- id PK AI UNIQUE BIGINT

table: condition
- id PK AI UNIQUE BIGINT

table: genre
- id PK AI UNIQUE BIGINT


