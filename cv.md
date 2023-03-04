# Iaroslav Gritsenko
![](https://sun9-8.userapi.com/impf/c631219/v631219631/6720/lE9RBX_sLHs.jpg?size=2160x1440&quality=96&sign=5ae5a56752ae8b7a76969d1613a30229&type=album)

# Contact
* E-mail: iar.gritsenko@gmail.com
* Discord: Yarko#1751

# Description
* I was always around PCs from 1990s, playing a lot of PC games, have a lot of friends who already in IT community and now i think it's time for me to join this feast of life to make some impact for IT.
* Jokes aside. I have an engineering structure of the mind. I had some practice with the "main" language of programming at the institute. I worked as a seller of clothes in my youth, magazine designer, design engineer and project manager in IT product with #### PostgreSQL experience around 1,5 year.

# Skills
* Great soft skills
* PostgreSQL
* Analyst
* Jira
* Git
* JSON
* CSS
* Agile

# Code example
## Codewars

### Task
Given two arrays a and b write a function comp(a, b) (orcompSame(a, b)) that checks whether the two arrays have the "same" elements, with the same multiplicities (the multiplicity of a member is the number of times it appears). "Same" means, here, that the elements in b are the elements in a squared, regardless of the order.

### Solution
```javascript
function comp(array1, array2) {
  let result = true;
  if (array1 === [] || array2 === [] || array1 === null || array2 === null) {
     return false
  }
  let arr1 = array1.sort((a, b) => a - b).map(a => a * a);
  let arr2 = array2.sort((a, b) => a - b).map(a => a);

  for (let i = 0; i < arr2.length; i++) {
        if (arr2[i] !== arr1[i]) {
          return false
        }
  }
  return result
};
```

# Work experience
1,5 years Middle Project Manager of InStat

# Education
* 1 year of Moscow State Institute of Electronic Technology
* Full education of the Russian State University of Trade and Economics (Master, Specialist)
* RS School JS/Frontend Stage #0
* RS School JS/Frontend Stage #1-2 (in progress)

# English level
* I hope so still B2.
* Lived 1 month in Prague and Berlin for the work.