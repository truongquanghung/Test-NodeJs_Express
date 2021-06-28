# Test-NodeJs_Express
Make web with NodeJs_Express
<br><br>
**Build new app**
<br>
<code> express -v [Template engine] [Name of App] 
<br>
npm install --save-dev nodemon
<br>
npm install </code>
<br><br>
**Add port for app server**
<br>
**_In file App.js_**
<br>
<code>
const port = process.env.PORT || 8080;
<br>
app.listen(port);
<br>
console.log('Server started at http://localhost:' + port);
</code>