Zamotina Darya

<img src="https://github.com/DaryaZamotina/rsschool-cv/assets/133055781/2dc793db-3d5c-40d0-acbc-51d85ac78783" width="200" height="200">


*Contacts* 
* e-mail: daryazamotina@gmail.com
* Telegram @DaryaZamotina
* Discord: Daria Zamotina (@daryazamotina)


*Brief intruduction*
Hello! My name is Darya and I'm 38. During more than 15 years I'm working in the field of the intellectual property protection, being the trademark attorney from 2014. Some months ago I came to the conclusion that I want some changes in my professional life and as a result I start to study Frontend. Beginning from self-education by learning different books and tutorials, I have found the courses of RS School and I really understand that studying among like-minded people under mentoring of professionals in the field of Frontend - such way will give me great results.


*Education*
University  | Period | Degree
:-----------: | :------: | :-------:
Saint-Petersburg State Polytechnic University, Physical and mechanical department |  09/2002 - 06/2006  | bachelor's degree of physics
Saint-Petersburg State Polytechnic University, Physical and mechanical department  | 09/2006 - 06/2008 | Master's degree of biophysics
Saint-Petersburg State Pedagogical University, Legal department  |  09/2009 - 10/2012  |  Civil law specialist
****
* Courses of Hexlet "Basic knowledges about modern layout", 2023; "Introduction into Git", 2023


*Skills*
* HTML
* CSS
* JavaScript
* Vue
* React
* Git


*Codes example in Codewars*

1. > 7 kyu  Shortest Word
DESCRIPTION:
Simple, given a string of words, return the length of the shortest word(s). String will never be empty and you do not need to account for different data types.

*Solution*
```
function findShort(s){
   let arr = s.split(' ');
        let arrLeng = [];
        for (let elem of arr) {
          arrLeng.push(elem.length);
        }
        let res = Math.min.apply(null, arrLeng);
  console.log(res);
  return res;
}
```

2. > 7 kyu Build a square
DESCRIPTION:
I will give you an integer. Give me back a shape that is as long and wide as the integer. The integer will be a whole number between 1 and 50.
 
 *Solution*
```
 function generateShape(integer){
 let arr = [];
        for (let i=0; i<integer; i++){
        arr.push("+");    
        }
 let res= arr.join('');
  res = res + '\n';
  let resFinal = '';
        
  for (let j=1; j<=integer; j++) {
      resFinal += res;
        }
  return resFinal.substr(0, resFinal.length-1);
}
```

*Work Experience*
During my self-education with the books I did my first steps in Frontend making first simplest sites, improving knowledges of `HTML` and `CSS`. 


*Language knowledges*
* English Language: B2-C1 level. 
Every working day I write business letters for our foreign clients in English,  from time to time it is necessary to communicate by phone with them describing and explaining cases for their better understanding.
* French (upper intermediate)
