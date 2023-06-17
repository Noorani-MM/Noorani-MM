 **Hi there** 👋🏻 
 
### About me 📖
<hr>

```php
class MySelf extends Human {

    protected $name = 'Mohammad Mahdi Noorani';
    
    protected $skills = [
        'php'        => 'Laravel', // API Developer
        'javascript' => 'Nuxt',
        'css'        => 'Tailwind css',
        'c#'         => '.net framework',
    ];

    public function __construct() {
        parent::__construct();
        $this->life_cycle();
    }

    protected function life_cycle() {
        do {
            $this->being_kind();
            $this->learning();
            $this->coding();
        } while ($this->alive()); 
    }
}
```
