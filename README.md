# crud-nodjs-postgree
Database

npm install postgresql

CREATE TABLE users (
  ID SERIAL PRIMARY KEY,
  name VARCHAR(30),
  email VARCHAR(30)
);

INSERT INTO users (name, email)
  VALUES ('Muhamad Lutfi kamil', 'kamillutfi505@example.com'), ('Rexy', 'Rexy@example.com');
  
  
Installation

git clone https://github.com/kamilmuhamad/crud-nodjs-postgree.git

npm install
node index.js
