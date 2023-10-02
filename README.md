
<img src="https://github.com/Taoshan98/Taoshan98/blob/main/Header.jpg" alt="Taoshan98_header">

<!-- Your title -->
### Hi, I'm Nunzio Marfè 👋🏻‍💻, a Developer from Naples, Italy. 🚀

[![Github](https://img.shields.io/badge/-@Taoshan98-000?style=flat&logo=Github&logoColor=white)](https://github.com/Taoshan98)
[![Linkedin](https://img.shields.io/badge/-@NunzioMarfè-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/nunzio-marf%C3%A8-854b79129/)
[![Instagram](https://img.shields.io/badge/-@Taoshan98-c13584?style=flat&labelColor=c13584&logo=instagram&logoColor=white)](https://www.instagram.com/taoshan98/)
[![Twitter Badge](https://img.shields.io/badge/-@NunzioMarfè-00acee?style=flat&logo=Twitter&logoColor=white)](https://twitter.com/intent/follow?screen_name=MarfeNunzio "Follow on Twitter")
[![StackOverflow](https://img.shields.io/badge/-NunzioMarfè-f48024?style=flat&labelColor=f48024&logo=stackoverflow&logoColor=white)](https://stackoverflow.com/users/8567455/nunzio-marf%c3%a9)
[![wakatime](https://wakatime.com/badge/user/76f25c7d-4358-404a-acd5-4fd46f1ae124.svg)](https://wakatime.com/@76f25c7d-4358-404a-acd5-4fd46f1ae124)

```php
<?php

namespace Taoshan;

class About extends Me
{
    protected array $myself = [
      'birthday' => '1998-10-25',
      'gender' => 'Male',
      'city' => 'Naples',
      'country' => 'Italy'
    ];

    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => '@GruppoTecno',
                'position' => 'Full Stack Web Developer',         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            React::class,
            ReactNative::class,
            MySQL::class,
            PostgresSQL::class,
            TimeScale::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Solving more and more bugs.';
    }
}
```

