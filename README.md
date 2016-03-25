## easy-datetime
a datetime util 

### usage

```bash
    npm install easy-datetime
```

### example

```javascript
    var DateTime = require('easy-datetime');
    
    var dateStr = new DateTime().format();
    
    var tommorow = new DateTime().next('date');
    
    var yesterday = new DateTime().prev('date');
    
    var days = new DateTime().countDays();
    
    var str = DateTime.format('yyyy-MM-dd',new Date());
 
```