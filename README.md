KRDictionaryExport
------------------

A category for NSManagedObject which exports a CoreData object into an NSDictionary, including all its relationships. The NSDictionary created is formatted for easy JSON-conversion using something like [JSONKit](https://github.com/johnezang/JSONKit) or NSJSONSerialization.

Usage
=====

```objective-c  
NSDictionary *dict = [yourCoreDataManagedObject asDictionary];  
// where 'yourCoreDataManagedObject' is the NSManagedObject you want to convert into a dictionary.  
```  

Todo
====

1. Support for NSData type
2. Sample app


Author
======

**Kishyr Ramdial**, proudly from Durban, South Africa.  
Twitter: [@kishyr](http://twitter.com/kishyr)  
App.net: [@kishyr](http://alpha.app.net/kishyr)  