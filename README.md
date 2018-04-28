# london.instech.overrides

## Requirements

* CiviCRM 5.0.2

## Overrides
### mail() backend fails when empty Cc and Bcc parameters are passed
https://lab.civicrm.org/dev/core/issues/85

* CRM/Utils/Mail.php

This file is overridden to unset empty Cc and Bcc headers as mail() on getflywheel.com won't send email if they are present.
