# london.instech.overrides

## Requirements

* CiviCRM 5.0.2

## Overrides
### CRM/Utils/Mail.php
This file is overridden to unset empty Cc and Bcc headers as mail() on getflywheel.com won't send email if they are present.
