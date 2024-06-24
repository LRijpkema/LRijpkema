<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <img src="https://media.giphy.com/media/mcsPU3SkKrYDdW3aAU/giphy.gif" alt="Cat Gif" style="width: 100%; max-width: 300px;">
  </div>
  <div style="flex: 2; padding-left: 20px;">
    <pre style="background-color: #f5f5f5; padding: 20px; border-radius: 8px;">
      <code>
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
      </code>
    </pre>
  </div>
</div>
