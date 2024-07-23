```php
<?php

namespace LuluRijpkema;

class About extends Me
{
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
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
