```php
class FullStackDeveloper {

    public string $name     = "Jennifer Martinez";
    public bool $researcher = true;
    public bool $developer  = true;
    public array $languages = ["en_CA", "es_MX", "pt_BR", "fr_CA"];
    public string $location = "Montreal, CQ";


    public function sayHi() {
        echo "I'm glad you read my intro! Please also visit my website carlostoxtli.com\n";
    }
}

$me = (new FullStackDeveloper())->sayHi();
```
