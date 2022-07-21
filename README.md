```php
$me = new Person(
    name:  'Maicol Kaiser Oliveira',
    email: 'maicol.oliveira@paygo-consult.com.br',
    age:  31
);

$me->setStatus(new Life\Status(
    learning: ['Clean Architecture', 'Object Calisthenics', 'Clean Code'],
    objectives: ['Improve my english', 'Cloud', 'Functional Programming']
));

$myAbilities = new Life\Abilities(
    languages:  ['HTML/CSS', 'PHP', 'Python', 'Shell', 'Javascript'],
    ide: ['VSCode', 'Notepad++'],
    frameworks: ['Jquery', 'Bootstrap', 'Laravel'],
    database: ['SQLite', 'Redis', 'Memcached', 'PostgreSQL', 'MySql'],
    knowledge:  [   
                    'DNS', 'Debian', 'WSL2', 'Git', 'Gitlab CI/CD', 'Markdown',
                    'CentOS', 'Rest', 'OSPF', 'BGP', 'MPLS', 'VLAN', 'Firewall',
                    'Docker/Docker Compose', 'Websocket', 'Ansible', 'Vagrant',  
                    'Zsh', 'Nginx', 'PHP-FPM', 'Jekyll', 'Memcached', 'Maillhog',
                    'Ubuntu', 'Github Actions'
                ]
);

$dev = new Occupation\Developer(person: $me, abilities: $myAbilities);

while($dev->hasCoffee())  
{
  $dev->code();
}
```

### Hi there 👋
---
I'm Maicol 👨🏻‍💻, a 31 years old Web Developer / Network Admin from Brazil.

- 🔭 I’m currently working on [C6 Bank](https://c6bank.com.br)
- 🌱 I’m currently learning [Design patterns](https://refactoring.guru/pt-br/design-patterns)
- 📫 How to reach me: 
    - [<img src="https://img.icons8.com/color/48/000000/linkedin.png" width="4%"/>](https://linkedin.com/in/maicolkaiseroliveira) [<img src="https://img.icons8.com/fluent/48/000000/instagram-new.png" width="4%"/>](https://www.instagram.com/maicolvk/) [<img src="https://img.icons8.com/color/48/000000/twitter.png" width="4%"/>](https://twitter.com/maicolvaka) <a href="mailto:maicol.oliveira@paygo-consult.com.br"> <img src="https://img.icons8.com/fluent/48/000000/gmail.png" width="4%"/>

    

### Skills 💪🧠
---
- <img src="https://www.php.net/favicon.ico" width="16" height="16" /> PHP
    - For a long time i've been working with PHP and is awesome how much tools that this incredible language have, i really love PHP.
- 🐳  Docker
    - In my point of view, containers are one of the most powerful tool that we have to maintains complex systems, and we need to learn how to work with.
- 💽 SQL
    - I've worked with some relational database like Postgres, Mysql, SQL Server, and again... in my point of view, to know SQL it is really important to any programmer nowadays.

I'm sorry about my english, is not my native language and i've been work to improve it 😅... then could you please correct me if I make any grammatical mistakes? thanks 🙏.