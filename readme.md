# MongoDB for Kohana 3.2

## Mango

Mango is an ORM/ActiveRecord like library that takes full advantage of MongoDB's features. Mango supports:
* **Atomic updates** - the library will calculate what values changed, and will update only those values using atomic modifiers like $set, $push/$pull and $inc
* **All Mongo datatypes** including embedded objects, arrays, enums and (multidimensional) counters
* Relationships you remember from the RDBMS world like has_one, belongs_to, has_many and has_and_belongs_to_many
* Validation of object data, including embedded objects
* Class Table Extension-like behavior - eg Model_Ferrari extends Model_Car extends Mango.
* Very easy syntax very familiar to users of other ORMs

## MangoDB

A simple wrapper to access MongoDB. Store your database info in a config file and access MongoDB from anywhere in your code using MangoDB::instance().

## MangoQueue

Want to implement a queue in MongoDB? Check MangoQueue: 
http://github.com/Wouterrr/mangoQueue
and
https://github.com/Wouterrr/MangoTask

## MangoUtils

Use MongoDB for Kohana Log? Kohana Sessions? Scaffolding? or ACL assertions?

Check:
https://github.com/Wouterrr/MangoUtils

## License

 "THE BEER-WARE LICENSE" (Revision 42):
 Wouter Wiegmans wrote this file. As long as you retain this notice you
 can do whatever you want with this stuff. If we meet some day, and you think
 this stuff is worth it, you can buy me a beer in return - Wouter Wiegmans
