```php
namespace LaJennyLove;

class FullStackDeveloper {

    public string $name     = "Jennifer E. Martinez 👩🏼‍💻✨";
    public bool $backend    = true;
    public bool $frontend   = true;
    public bool $devops     = true;
    public bool $mobile     = true;
    public array $languages = ["en_CA" => 🇨🇦, "es_MX" => 🇲🇽, "pt_BR" => 🇧🇷, "fr_CA" => 🇨🇦];
    public string $location = "📍 Montreal, Qc";


    public function whelloWorld()
    {
        echo "I’m going to have to science the shit out of this. 🚀 \n";
    }
}

$me = (new FullStackDeveloper())->helloWorld();
```
