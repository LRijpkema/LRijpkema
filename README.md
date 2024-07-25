```php
<?php

namespace LuluRijpkema;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'OGonline'
                'position' => 'Front-End Developer'
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Javascript::class,
            Laravel::class,
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
