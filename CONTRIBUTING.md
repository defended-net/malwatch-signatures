A heartfelt thank you for your interest in contributing! A great malware detection rate hinges on a robust signature set.

This document serves to outline basic rule formatting and requirements.

## Naming

- Rule names as well as meta fields should please be **lowercase**. This avoids unnecessary complexity for parsing fields.

- Rule names should please be reasonably short.

- A prefix which describes the category of malware should please be included.  It should then please be followed
by the language. Lastly, there should be a numeric identifier to signify the variant. Full example:

`shell_php_name_0`

We start as `0` because that will avoid confusion when iterating. Most programming languages also begin array indexes with `0`.

## Meta

- Please include your name / pseudonym as the `author` plus a brief `description`.

- The `description` field should please end with a full stop `.`.

No further meta fields are allowed.

## Licence

- Our `defended` signature set applies the `CC BY-NC-SA 4.0` licence. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0