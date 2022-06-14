# Andrei Protska
## Contact Information

* **Phone:** +375255076635
* **E-mail:** [prockaandrei@gmail.com](prockaandrei@gmail.com)
* **Telegram:** [https://t.me/protska_andrei](@protska_andrei)

# About Me
I am a beginner web developer, interested in developing web applications and web services.

# Skills
* HTML,CSS
* JavaScript(Fundamentals, Functional Programming)
* Version control: GitHub, GitLab
* Python(Fundamentals, Functional Programming, OOP) - Django Framework(basic knowledge), SQLite(basic knowledge), PostgreSQL(basic knowledge).
* Windows, Linux
* Editors: PyCharm community, VSCode, Vim.

### Code examples Python
**Task:** Print the specified list and possible subscriptions, including the empty list.
```
line = input().split()
length_line = len(line)
result_list = [[]]

k = 1
while length_line != 0:
    for i in range(length_line):
        result_list.append(line[i:i + k])
    k += 1
    length_line -= 1
print(result_list)
```

### Code examples JavaScript
**Task:** Write simple .camelCase method (camel_case function in PHP, CamelCase in C# or camelCase in Java) for strings. All words must have their first letter capitalized without spaces.
```
String.prototype.camelCase=function(){
   return this.split(' ').map(function(word){
    return word.charAt(0).toUpperCase() + word.slice(1);
  }).join('');
}
```

# Education
* **Stepik:** Basics of Python programming in examples and tasks [cert](https://stepik.org/cert/1154382)
* **Stepik:** Python Generation: a course for beginners [cert](https://stepik.org/cert/1318773)
* **Stepik:** Python Programming [cert](https://stepik.org/cert/1410141)

# Languages
- Russian
- Belarusian
- English **A1** ([EPAM English test result](https://examinator.epam.com/Main/PersonalAssignments))
