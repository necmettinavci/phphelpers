## PHP Helpers 

**Install**
```
  composer require necmettinavci/phphelpers
``` 

**Usage**

```
  <?php
      require_once "./vendor/autoload.php";
      use necmettinavci\PhpHelpers\PhpHelpers;
      
      $nameArray = PhpHelpers::separateFullName('Shah Rukh Khan');
      print_r($nameArray);
      // Output: Array ( [0] => Shah Rukh [1] => Khan )

```