# Javascript-loop-substring

![javascript loop, substring ocde](https://github.com/user-attachments/assets/208d237c-29e4-4106-8a65-7ed0fc13ed13)
![javascript loop, substring](https://github.com/user-attachments/assets/7ee022a6-a76a-430c-af6e-5acd07dfe4cf)


let i= 1;
while(i==1){
   console.log("dsfsd");
   break;
}
for(let i=1; i<4;i++){
    console.log("sdf");
}
let name= "naiman";
let nameq=`yes 
boy`;
console.log(nameq);

let op1= "naiman";
let op2='yes';
console.log(op1.length);
console.log(op1.toUpperCase());
console.log(op1.toLocaleLowerCase());

let string1 =  "Namaste";
console.log(typeof(string1));     
let string2 =  "Namaste";
console.log(string2.substring(3));      
let length = string1.length;
console.log(length);      

let startIndex=1;
let endIndex=4;
string1.substring(startIndex, endIndex);
console.log(length); 
let startIndex1="dfsdfsdf afsdfsdf vhfchfhfg";
let  words= startIndex1.split(' ');
console.log(words);
let startIndex2="dfsdfsdf \\afsdfsdf \\vhfchfhfg";
let  words1= startIndex2.split('\\');
console.log(words1);
console.log(words1.join(" "));
