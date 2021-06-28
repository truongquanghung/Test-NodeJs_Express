# Test-NodeJs_Express
Make web with NodeJs_Express
<br><br>
**Build new app**
<br>
```powershell
express -v [Template engine] [Name of App] 
npm install --save-dev nodemon
npm install
```
<br><br>
**Add port for app server**
<br>
**_In file App.js_**
<br>
```js
const port = process.env.PORT || 8080;
app.listen(port);
console.log('Server started at http://localhost:' + port);
```
