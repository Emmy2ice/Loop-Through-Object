# Loop-Through-Object
A mini task on skeelup.netlify.app to loop through objects
const objectName = {
name: 'test',
age: 21,
country: 'Earth'
};
for (let key in objectName){
if (objectName.hasOwnProperty(key))
console.log(key + ":" + objectName[key]);
}
