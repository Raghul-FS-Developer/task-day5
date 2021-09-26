(!).
(function(){
     for(i=1; i<=100; i++){
       if(i % 2 != 0){
    console.log(i);
  }
     }
       
})()





(2).
function sentenceCase (str) {
  if ((str===null) || (str===''))
       return false;
  else
   str = str.toString();
  
 return str.replace(/\w\S*/g, 
function(txt){return txt.charAt(0).toUpperCase() +
       txt.substr(1).toLowerCase();});
}
  
document.write(sentenceCase('guvi is the best'));



(3).
const array = [1, 2, 3, 4]; 
let sum = 0;
for (let i = 0; i < array. length; i++) { 
  sum += array[i]; 
}
console. log(sum)




(4)











