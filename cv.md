
# Aliaksei Palityka



## Contact Info



* E-mail: a.polityko@mail.ru;
* Discord: [Oscarishe](https://discord.com/users/278415841802977280);
* GitHub: [Oscarishe](https://github.com/oscarishe).

Location: Minsk, Belarus(GMT+3)

## My Skills



* HTML5;
* CSS3;
* JavaScript (Fundamentals, Basic of React Framework);
* SQL;
* MongoDB;
* Java Spring Framework;
* Git;
* Design Patterns;
* IDE: WebStorm, IntelliJ IDEA, NetBeans, Visual Studio, Sublime.

## Code examples 



> The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.

```
function duplicateEncode(word){
  word = word.toLowerCase();
  let result = [];
    for(var i = 0; i < word.length; i++) {
        for(var j = 0; j <= word.length; j++) {
            if(word[j] == word[i] && j!=i) {
                result.push(')');
                break;
              }
            if(j==word.length)
                result.push('(');
        }
    }
    return result.join('');
}
```

## My experience 



Creating front-end side of samp-leader.ru (project was closed in 2018), which provides different services to San Andreas Multiplayer players. Also in this project, I was responsible for website design, business analysis, copywriting and social media marketing.

## Education 



* Belarusian State University of Informatics and Radioelectronics (Faculty of Engineering and Economics bachelor), 2021;
* HTMLAcademy courses (Basics and subscription advanced courses) - ([profile](https://htmlacademy.ru/profile/id107318))



## Language skills



* Russian: native speaker;
* Belarusian: native speaker;
* English: B1 (EPAM testing).
