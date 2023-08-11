# UseJObject

Example to use JObject with UiPath
---

## Step by Step
First create variable in scope
```
jObject
jObjectString
```
![variables](https://github.com/echicasprado/UseJObject/blob/main/img/variables.PNG)

Then add data into jObject
```
jObject["author"] = "Miguel Ángel Asturias Rosales"
jObject["pages"] = "Señor presidente"
jObject["pages"] = "321"
```
![assig Data](https://github.com/echicasprado/UseJObject/blob/main/img/assigData.PNG)
Finally use JsonConvert to convert from jObject to String

```
jObjectString = JsonConvert.SerializeObject(jObject)
```
---
Final result
### JObject
Log
![jObject](https://github.com/echicasprado/UseJObject/blob/main/img/jObjectLog.PNG)
Result
![jObject result](https://github.com/echicasprado/UseJObject/blob/main/img/resultJObjectLog.PNG)
### String
Log
![string](https://github.com/echicasprado/UseJObject/blob/main/img/stringLog.PNG)
Result
![string result](https://github.com/echicasprado/UseJObject/blob/main/img/resultStringLog.PNG)
