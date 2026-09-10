```php
<?php

namespace AleBorellini;

class Me extends Person
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'SAY S.p.a.',
                'position' => 'Web Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            PHP::class,
            Laravel::class,
            JavaScript::class,
            MVCArchitecture::class,
            Sass::class,
            TailwindCss::class,
            Shopify::class,
            MySQL::class,
            Docker::class,
            Git::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Learning more & more stuff and perhaps try to spread the knowledge';
    }
}
```

- 🌱 Learning Vue.js / Nuxt.js / Three.js / Headless CMS (Strapi)
- ⚡ Fun fact: The reason for my GitHub username? Because of my profile photo 🌭
