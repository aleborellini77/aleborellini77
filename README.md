### Hello world

```php
<?php

namespace AleBorellini;

class Me extends Person
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => ‘YAK Agency’,
                'position' => ‘Web Developer’         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
	          Laravel::class,
            Javascript::class,
            MVCArchitecture::class,
            SASS::class,
            TailwindCss::class,
            GSAP::class,
            Liquid::class,
            MySQL::class,
            Docker::class,
            Git::class
        ];
    }

    public function getDailyEntertainmentWith(): array
    {
        return [
             Linux::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return ‘Learning more & more stuff and perhaps try to spread the knowledge’;
    }
}
```

- 🌱 Next goal to learn React / Next.js / Vue.js / Nuxt.js / Headless CMS (Strapi-Contentful-Storyblok)
- ⚡ Fun fact: The reason for my GitHub username? Because of my profile photo 🌭
