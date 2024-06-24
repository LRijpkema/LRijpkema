<div>
<div style="text-align: center;">
  <img src="https://media.giphy.com/media/mcsPU3SkKrYDdW3aAU/giphy.gif" alt="Cat Gif" style="width: 100%; max-width: 600px;">
</div>

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
