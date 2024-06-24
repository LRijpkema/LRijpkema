```php
<?php

namespace LuluRijpkema;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Modern Media Hub'
                'position' => 'Intern'
            ]
        ];
    }

    public function getKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            TailwindCss::class,
        ];
    }
}
```
</div>
