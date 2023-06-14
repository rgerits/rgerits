# Hello, I'm Ronald Gerits!
Application developers

## Certifications:
- Laravel Certified
- Pending: Vue Certified

Laravel certified! :smiley:
## Stack used
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white) 
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vue.Js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Confluence](https://img.shields.io/badge/confluence-%23172BF4.svg?style=for-the-badge&logo=confluence&logoColor=white)
![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black)


## Looking for & work experience
```php
<?php

namespace App\Models;

use Illuminate\Notifications\Notifiable;
use Illuminate\Foundation\Auth\User;
use Illuminate\Support\Collection;

class Ronald extends User
{
    use Notifiable;
    
    public function laravelCertified(User $user)
    {
        if($person->name == "Ronald Gerits") return true;
        else return null;
    }

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
                'current' => false
            ],
        ]);
    }
}
```
# Dino all day long :-)
![Alt Text](https://github.com/rgerits/rgerits/blob/main/dino.gif)
