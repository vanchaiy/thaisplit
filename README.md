# thaisplit
thaisplit for Php pure &amp; support larave
แยกคำประโยคภาษาไทย

INSTALLATION
------------

Run Composer in your project:

    composer require vanchaiy/thaisplit
    
Then you could use SDK class after Composer is loaded on your PHP project:

```php
require __DIR__ . '/vendor/autoload.php';

$exp = new THSplit\Segment();
```

### Test

```php
$exp = new THSplit\Segment();

print_r($exp->get_segment_array("ทดสอบแยกคำข้อความภาษาไทย"))
```
```array
Array ( [0] => ทดสอบ [1] => แยก [2] => คำ [3] => ข้อความ [4] => ภาษาไทย )
```

