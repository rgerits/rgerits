```php
<?php

namespace App\Models;

use Illuminate\Notifications\Notifiable;
use Illuminate\Foundation\Auth\User;
use Illuminate\Support\Collection;

class Ronald extends User
{
    use Notifiable;

    public function lookingFor()
    {
        return cache()->remember('lookingfor', now()->addMonth(6), fn() => [
            'job' => 'Freelance consultancy',
            'parttime' => true,
            'hours' => [
                'minimum' => 1,
                'maximum' => 15,
                'comment' => 'This is always negotiable',
            ]
        ]);
    }

    public function workExperience()
    {
        return collect([
            [
                'companyName' => 'Gerits Consultancy',
                'role' => 'Owner',
                'current' => true
            ],
            [
                'companyName' => 'Taghopper',
                'role' => 'Owner / developer',
                'current' => true
            ],
            [
                'companyName' => 'Remote Syslog',
                'role' => 'Laravel developer',
                'current' => false],
        ]);
    }

    public function skills()
    {
        return ['laravel', 'html', 'git', 'docker', 'PHP', 'test driven development'];
    }
}
```
# Dino all day long :-)
![Alt Text](https://github.com/rgerits/rgerits/blob/main/dino.gif)
