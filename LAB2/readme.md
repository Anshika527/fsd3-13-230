# crud operation on files

1.fs=(file system) Node JS's module - interact directly with os , node library,helps in 2.2.2. reading file in small chunks intsead of loading the whle at once ,streaming is onne example
3.c-crud,r-retrieve,u-update,d-delete 4. reading and writing files
-readFile()
-writeFile()
-appendFile()

# directory management

    -mkdir()
    -rmdir()
    -readdir()

# metadata

    fstat()

# watching for changes

    -watch()
    -watchFile()
    -unwatchFile()

# straming large file

     -createReadStream()
     -createWritestream()

# File opeartions

     -rename()
     -truncate()
     -unlik()
     -link()
     -syslink()

## CRUD operation

    create/ insert, read/retrive,update,delete

## Item

id ,name,price,qty

## operations

1. add to cart
2. show cart
3. remove item from cart
4. checkout
   NOTE : all items will be stored in hdd, so after termination of program we can retrieve cart details

## required files

1. crud.js - it contains all the methods and eentry point
2. products.json -it contains the product details in array form
