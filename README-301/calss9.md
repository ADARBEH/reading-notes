## What is functional programming?

#### unctional programming is a programming paradigm where programs are constructed by applying and composing functions. It is a declarative programming paradigm in which function definitions are trees of expressions that map values to other values

---
## What is a pure function and how do we know if something is a pure function?

#### Pure functions are the atomic building blocks in functional programming. They are adored for their simplicity and testability.

---
## What are the benefits of a pure function?

#### A pure function works as an independent function that gives the same output for the same inputs. Pure functions are readable because of independent behavior. Moreover, they are straightforward to debug. You can clone an external state into a pure function, but it does not change the purity of the function

---
## What is immutability?
#### In object-oriented and functional programming, an immutable object  is an object whose state cannot be modified after it is created
---
## What is Referential transparency?

#### referential transparency and referential opacity are properties of parts of computer programs. An expression is called referentially transparent if it can be replaced with its corresponding value (and vice-versa) without changing the program's behavior
---

### What is a module?

- #### The module is basically another javascript file.

### What does the word ‘require’ do?

- #### it's a method used to call a module where the application need

### How do we bring another module into the file the we are working in?

- #### `require ("module path").`

### What do we have to do to make a module available?
- #### `we use module.exports`