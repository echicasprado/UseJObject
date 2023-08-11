# UseJObject

Example to use JObject with UiPath

## Step by Step
Click in Manage Packages

![Manage Packages](https://github.com/echicasprado/UseJObject/blob/main/img/packageManage.PNG)

- Find UiPath.WebAPI.Activies
- Click on install
- Save

![WebAPI](https://github.com/echicasprado/UseJObject/blob/main/img/WebAPI.PNG)

Check package name in dependencies

![Check package](https://github.com/echicasprado/UseJObject/blob/main/img/checkPackage.PNG)

Create variable in scope
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

## Final result

### JObject
![jObject](https://github.com/echicasprado/UseJObject/blob/main/img/jObjectLog.PNG)

![jObject result](https://github.com/echicasprado/UseJObject/blob/main/img/resultJObjectLog.PNG)

### String
![string](https://github.com/echicasprado/UseJObject/blob/main/img/stringLog.PNG)

![string result](https://github.com/echicasprado/UseJObject/blob/main/img/resultStringLog.PNG)
