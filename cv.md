# Davyd Kuzikevich

# Contacts
 - [davyd.kuzikevich@gmail.com](davyd.kuzikevich@gmail.com)
 - +375 (33) 310-96-57
 - Discord: @Дичьсан#3763
 - GitHub: [KuzikevichDavid](https://github.com/KuzikevichDavid)

# About
  My strengths are problem solving and teamwork. I want to learn web technologies. 

# Practical Skills
 - Oracle DB
 - SQL, PL/SQL
 - XML/XSL/XSLT
 - C#, TypeScript/JavaScript, Java 
 - HTML/CSS
 - MS Visual Studio, Visual Studio Code, SQL Navigator for Oracle
 - Docker
 - Git

# Code example
Codewars [Who is the killer?](https://www.codewars.com/kata/5f709c8fb0d88300292a7a9d)
```js
 function killer(suspectInfo, dead) {
   const suspect = Object.values(suspectInfo);
   let result = 0;
   for (let i = 0 ; i < suspect.length; i++) {
     let count = 0;
     for (let j = 0; j < suspect[i].length; j++) {
       if (dead.findIndex((deadItem) => deadItem === suspect[i][j]) >= 0) {
         count++;
       }
     }
     if (count === dead.length) {
       result = i;
       break;
     }
   }
   
   return Object.keys(suspectInfo)[result];
 }
```
# Education
 - **2015** Yanka Kupala State University of Grodno / Mathematics and Informatics

# Experience
Work as sql, pl/sql developer during 7 years.

# Languages
 - English A2
 - Russian - native speaker
 