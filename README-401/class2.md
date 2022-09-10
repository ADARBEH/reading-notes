
## What's the difference between SQL and NoSQL?

  

-  #### SQL databases are relational, NoSQL databases are non-relational.

  

-  #### SQL databases use structured query language and have a predefined schema. NoSQL databases have dynamic schemas for unstructured data.

  

-  #### SQL databases are vertically scalable, while NoSQL databases are horizontally scalable.

  

-  #### SQL databases are table-based, while NoSQL databases are document, key-value, graph, or wide-column stores.

  

-  #### SQL databases are better for multi-row transactions, while NoSQL is better for unstructured data like documents or JSON.

  

  

---

  

## What is Sequlize and how to use it with Node js?

  

-  #### Sequelize is a promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server. It features solid transaction support, relations, read replication and more.

  

-  #### how to use it

  

1.  #### install sequelize-cli

  

```
npm install sequelize sqlite3
```

  

2.  #### DEFINE MODELS

  

```
import { Sequelize, Model, DataTypes } from 'sequelize';

const sequelize = new Sequelize('sqlite::memory:');
const User = sequelize.define('User', {
  username: DataTypes.STRING,
  birthday: DataTypes.DATE,
});
```

  

3.  #### PERSIST AND QUERY

```
const jane = await User.create({
  username: 'janedoe',
  birthday: new Date(1980, 6, 20),
});

const users = await User.findAll();;
```

---

## What is an ORM, how does it work, and how should I use one?
#### ORM stands for Object Relational Mapping. It is a technique that lets you query and manipulate data from a database using an object-oriented paradigm. In other words, it lets you create, read, update, and delete data from a database using an object-oriented paradigm.

---
# Preview

- ### Which 3 things had you heard about previously and now have better clarity on? some info about SQL and mongodb

- ### Which 3 things are you hoping to learn more about in the upcoming lecture/demo? i think i need more info about same two SQL and mongodb

- ### What are you most excited about trying to implement or see how it works? about table of SQL and how use it in advanced level