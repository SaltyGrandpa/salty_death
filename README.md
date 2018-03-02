# [Salty] Death
Adds protection against combat logging by saving death status to the database.

## Requirements
EssentialMode Extended, MySQL Async

## Instructions
Downloads folder, modify database, start the resource.

## Database Modification
```
ALTER TABLE `users` ADD `isDead` INT NOT NULL DEFAULT '0' AFTER `name`;
```
