```
function strCount(objeto) {
    let count = 0;
    for (key in objeto) {
      if (typeof objeto[key] == "string") count++;
      if (typeof objeto[key] == "object") count += strCount(objeto[key]);
    }
    return count;
  }
```
