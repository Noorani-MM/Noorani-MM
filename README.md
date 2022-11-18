 **Hi there** 👋🏻 
 
### About me 📖
<hr>

```php
class MySelf extends Human {

    protected $name = 'Mohammad Mahdi Noorani';
    
    protected $skills = [
        'php' => 'laravel', // API Developer
    ];

    public function __construct() {
        life_cycle();
    }

    protected function life_cycle() {
        do {
            being_kind();
            learning();
            coding();
        } while (self::ALIVE); 
    }
}
```