```php
<?php

namespace LuluRijpkema;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'position' => 'Intern'
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Svelte::class,
            TailwindCss::class,
        ];
    }

    public function getLocation(): string
    {
        return 'The Hague, Netherlands';
    }
}
```
</div>
