<h2> Hello, I'm Nathan :wave:</h2>

```php
<?php

class Developer {
    public $name;
    public $job;
    public $language_spoken;

    public function __construct() {
        $this->name = "Nathan Gaillard";
        $this->job = "Fullstack Developer";
        $this->language_spoken = ["fr", "en"];
    }

    public function say_hi() {
        echo "Hello, welcome to my GitHub page !";
    }
}

$developer = new Developer();
$developer->say_hi();


?>
```
