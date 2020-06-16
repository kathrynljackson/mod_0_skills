# class_1.md


## Class: Dish


### Attributes

`allClean` (Boolean): whether or not the item is clean, true = clean, false = not clean

`type` (string): the specific version of the item

`material` (string): what the item is made out of

`inventory` (integer): how many of that item currently owned 



### Methods

`cleanNow` (modifies `allClean`; if false, changes the `allClean` status to true)

`diffType` (modifies `type`; changes the `type` status to label the item as a different type)

`changeMat` (modifies `material`; changes material/textile of the object)

`buyMore`(uses `inventory`; adds 1 to the total number of objects)
