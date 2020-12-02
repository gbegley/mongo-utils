# mongo-utils
MongoDB Utilities


Usage:

```javascript
load("Utils.js")
load("Logger.js")
  
log.debug('A debugging message')
log.info('Some Info Message')
log.warn('Some warning')
log.error('Some error')
```

or for json logging...

```javascript
log.info('In 2021, Pi will be delicious',{'pi':3.14159265359});
```

Output:

```
20210314:159265 [INFO] In 2021, Pi will be delicious
{
   "pi" : 3.14159265359
}
```
  
