KnockoutJS-brackets 0.0.3
===================

Knockout extension for brackets. It's currently work-in-progress. 
Ideas, contributions and any other support are welcome! Especially some creative ideas, features you would like to see!

## Release notes

### 0.0.3
* Tested for brackets 1.0.0. Older versions of brackets may work, but I set 1.0.0 as lowest requirement. You can still use 0.0.2. 
* Removed deprecated function usages.
* Single cursor quick-edit inside a computed name now works.

### 0.0.2
* ko.computed quick-edit works for names with numbers and underscores as well.

### 0.0.1
* First working version 
* Quick-edit for ko.computed. (Not works with numbers in computed name and only works when you fully select the computed's name.)


What is currently working
-----------
Quick-edit for ko.computed.
This feature will be extended in next versions.


Currently planning to implement:
-----------
* Unit-tests. 
* More refactoring and improving current ko.computed functionality.

Quick-edit for:
* ko.observable ?
* subscribes ?

Thanks to:
-----------
* Adobe, for creating brackets (and making it open-source).
* The creator of the AngularJS-brackets extension, AngularUI. Gave me inspiration to create this knockout version that works on a the not-deprecated API's.
