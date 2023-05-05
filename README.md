
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=%D0%A3+%D0%BB%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D1%96%D0%B9+%D1%80%D0%BE%D0%B1%D0%BE%D1%82%D1%96+%D0%BC%D0%B8%3A) 
+ Створили обліковий запис GitHub:  
![](s1.png)  

+ Встановили CHOCOLATEY за допомогою наступного коду:  
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
+ Перевірили версію:  
![](s2.png)  
+ Встановили Git за допомогою наступного коду та перевірили версію:  
```
choco install git -y
```
![](s3.png)  
+ Виконали перші налаштування Git:  
```
git config --global user.name "RuslanSheiko"  
git config --global user.email r.o.sheiko@student.khai.edu  
```
+ Перевірили застосування налаштувань наступним кодом:  
```
git config --list
```
![](s4.png)  
+ Згенерували новий SSH ключ та додали його до облікового запсу Github:  
```
ssh-keygen -t ed25519 -C "r.o.sheiko@student.khai.edu"
```
![](s5.png)  
+ Створили новий репозиторій, назва відповідає нікнейму:  

![](s6.png)  

+ Зробили копію репозиторію на локальний комп'ютер, використовуючи ssh-ключ та код:  
![](s7.png)  
```
git clone git@github.com:RuslanSheiko/LR1.git
```

+ Додали опис профілю Github за допомогою наступних команд:  
```
git add .
git commit -m "Add your comment"
git push
```
<<<<<<< HEAD
+ Отримали наступний результат
![](s8.png)

+ Висновок

У лабораторній роботі навчилися працювати з git та GitHub. Було створено новий профіль в GitHub та оформлено. Встановили CHOCOLATEY та git з його допомогою. Під'єднали git та GitHub, вивантажи локальний репозиторій з основною інформацією про власника.

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=THE+END)
=======
+ Отримали наступний результат  
![](s8.png)  
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=THE+END)
>>>>>>> 67e87902a7bfcfbd7f0aa084b639c8ba043ba961
