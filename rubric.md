## Functional

* [ ] Has a `User` table
    * [ ] Self-joins on `referred_by`
    * [ ] Has a primary key
    * [ ] Can represent names, avatar urls, email, and username
* [ ] Has a `Review` table
    * [ ] Has a primary key
    * [ ] Has a foreign key for `User`
    * [ ] Has a foreign key for `Restaurant`
    * [ ] Can represent title, content, and rating
* [ ] Has a `Restaurant` table
    * [ ] Has a primary key
    * [ ] Has a foreign key for `User`
    * [ ] Can represent name, category, and URL
    * [ ] Represents paleo option as a boolean
* [ ] Has a `Menu_Item` table
    * [ ] Has a primary key
    * [ ] Can represent name, calories as an integer
* [ ] Has a join table between `Restaurant` and `Menu_Item` tables
    * [ ] Has a foreign key for `Menu_Item`
    * [ ] Has a foreign key for `Restaurant`
    * [ ] Has a price attribute that is `double`, `float`, or similar

## Stylistic

* [ ] No crossing lines in relationships
* [ ] Crows feet point to foreign keys
* [ ] Table names are singular
* [ ] Every table has 3 columns: 1 for key-type identification, 1 for name of column and 1 for the data-type
