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
