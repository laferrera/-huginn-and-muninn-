
let newCrow; const hugAndMun = require('./index'); hugAndMun().then((crow) => { newCrow = crow; console.log("we set it?", newCrow)})
let cb = (data) => { console.log("data", data) }; newCrow.setCallback(cb)
newCrow.helloWorld();
