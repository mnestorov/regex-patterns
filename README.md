# European Phone Numbers and Postal Codes Regex Patterns

![Licence](https://img.shields.io/badge/Unlicense-red)

## Overview

This repository contains regular expression (regex) patterns for validating phone numbers and postal codes for European countries. 

Below are the patterns for each country, along with a brief description.

## Contents
- [Regex Patterns](#regex-patterns)
  - 🇦🇩 [Andorra](#andorra)
  - 🇦🇹 [Austria](#austria)
  - 🇧🇪 [Belgium](#belgium)
  - 🇧🇦 [Bosnia and Herzegovina](#bosnia-and-herzegovina)
  - 🇧🇬 [Bulgaria](#bulgaria)
  - 🇭🇷 [Croatia](#croatia)
  - 🇨🇾 [Cyprus](#cyprus)
  - 🇨🇿 [Czech Republic](#czech-republic)
  - 🇩🇰 [Denmark](#denmark)
  - 🇪🇪 [Estonia](#estonia)
  - 🇫🇮 [Finland](#finland)
  - 🇫🇷 [France](#france)
  - 🇩🇪 [Germany](#germany)
  - 🇬🇷 [Greece](#greece)
  - 🇭🇺 [Hungary](#hungary)
  - 🇮🇪 [Ireland](#ireland)
  - 🇮🇹 [Italy](#italy)
  - 🇱🇻 [Latvia](#latvia)
  - 🇱🇮 [Liechtenstein](#liechtenstein)
  - 🇱🇹 [Lithuania](#lithuania)
  - 🇱🇺 [Luxembourg](#luxembourg)
  - 🇲🇹 [Malta](#malta)
  - 🇲🇪 [Montenegro](#montenegro)
  - 🇲🇨 [Monaco](#monaco)
  - 🇳🇱 [Netherlands](#netherlands)
  - 🇲🇰 [North Macedonia](#north-macedonia)
  - 🇳🇴 [Norway](#norway)
  - 🇵🇱 [Poland](#poland)
  - 🇵🇹 [Portugal](#portugal)
  - 🇷🇴 [Romania](#romania)
  - 🇸🇲 [San Marino](#san-marino)
  - 🇷🇸 [Serbia](#serbia)
  - 🇸🇰 [Slovakia](#slovakia)
  - 🇸🇮 [Slovenia](#slovenia)
  - 🇪🇸 [Spain](#spain)
  - 🇸🇪 [Sweden](#sweden)
  - 🇨🇭 [Switzerland](#switzerland)
  - 🇬🇧 [United Kingdom](#united-kingdom)
- [Usage](#usage)
  - [PHP](#php)
  - [Python](#python)
  - [C#](#c)
  - [Java](#java)
  - [Ruby](#ruby)
  - [JavaScript](#javascript)

## Regex Patterns

### Phone Numbers

#### Andorra
##### Phone Number
- **Pattern:** `^\\+376[0-9]{6}$`
- **Description:** Andorran phone numbers start with +376, followed by 6 digits.
##### Postal Code
- **Pattern:** `^AD\\d{3}$`
- **Description:** Andorran postal codes start with "AD" followed by 3 digits.

---

#### Austria
##### Phone Number
- **Pattern:** `^\\+43[1-9][0-9]{3,12}$`
- **Description:** Austrian phone numbers start with +43, followed by a non-zero digit and 3 to 12 more digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Austrian postal codes are made up of 4 digits.

---

#### Belgium
##### Phone Number
- **Pattern:** `^\\+32[1-9][0-9]{7,8}$`
- **Description:** Belgian phone numbers typically start with +32, followed by a non-zero digit and then 7 to 8 additional digits. This pattern caters to both mobile and landline numbers.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Belgian postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.
- 
---

#### Bosnia and Herzegovina
##### Phone Number
- **Pattern:** `^\\+387[6][0-9]{7}$`
- **Description:** Bosnian phone numbers typically start with +387, followed by a 6 (indicating a mobile number) and then 7 more digits. This pattern is tailored towards mobile numbers, as they are the most commonly used.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Bosnian postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.

---

#### Bulgaria
##### Phone Number
- **Pattern:** `^\\+359[1-9][0-9]{7,8}$`
- **Description:** Bulgarian phone numbers begin with +359, followed by a non-zero digit and 7 to 8 additional digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Bulgarian postal codes consist of 4 digits.

---

#### Croatia
##### Phone Number
- **Pattern:** `^\\+385[1-9][0-9]{7,8}$`
- **Description:** Croatian phone numbers start with +385, followed by a non-zero digit and 7 to 8 more digits.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Croatian postal codes are made up of 5 digits.

---

#### Cyprus
##### Phone Number
- **Pattern:** `^\\+357[2-9][0-9]{6,7}$`
- **Description:** Cypriot phone numbers start with +357, followed by a digit between 2 and 9, and then 6 to 7 more digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Cypriot postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.

---

#### Czech Republic
##### Phone Number
- **Pattern:** `^\\+420[1-9][0-9]{8}$`
- **Description:** Matches Czech phone numbers. Begins with +420 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Matches Czech postal codes, consisting of three digits, an optional space, and two more digits.

---

#### Denmark
##### Phone Number
- **Pattern:** `^\\+45[2-9][0-9]{7}$`
- **Description:** Danish phone numbers begin with +45, followed by a digit between 2 and 9, and then 7 more digits. This pattern covers the standard 8-digit format after the country code.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Danish postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.

---

#### Estonia
##### Phone Number
- **Pattern:** `^\\+372[5-9][0-9]{6,7}$`
- **Description:** Estonian phone numbers start with +372, followed by a digit between 5
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Estonian postal codes consist of 5 digits.

---

#### Finland
##### Phone Number
- **Pattern:** `^\\+358[1-9][0-9]{4,11}$`
- **Description:** Finnish phone numbers start with +358, followed by a non-zero digit, and then 4 to 11 more digits.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Finnish postal codes consist of 5 digits.

---

#### France
##### Phone Number
- **Pattern:** `^\\+33[1-9][0-9]{8}$`
- **Description:** Matches French phone numbers. Begins with +33 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** French postal codes are also 5 digits in length. This pattern matches a sequence of five numerical digits.

---

#### Germany
##### Phone Number
- **Pattern:** `^\\+49[1-9][0-9]{1,14}$`
- **Description:** Matches German phone numbers. Begins with +49 and is followed by 9 to 15 digits.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** German postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.

---

#### Greece
##### Phone Number
- **Pattern:** `^\\+30[2-9][0-9]{9}$`
- **Description:** Matches Greek phone numbers. Begins with +30, followed by a digit from 2 to 9, and then 9 more digits.
##### Postal Code
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Matches Greek postal codes, consisting of three digits, an optional space, and two more digits.

---

#### Hungary
##### Phone Number
- **Pattern:** `^\\+36[1-9][0-9]{8}$`
- **Description:** Hungarian phone numbers begin with +36, followed by a non-zero digit and 8 additional digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Hungarian postal codes consist of 4 digits.

---

#### Ireland
##### Phone Number
- **Pattern:** `^\\+353[1-9][0-9]{6,9}$`
- **Description:** Irish phone numbers begin with +353, followed by a non-zero digit, and then 6 to 9 more digits.
##### Postal Code
- **Pattern:** `^(D6W|[A-Z]{1}[0-9]{1,2}|[A-Z]{2}[0-9]{1,2}|[A-Z]{1}[0-9]{1}[A-Z]{1}|[A-Z]{2}[0-9]{1}[A-Z]{1})$`
- **Description:** Irish postal codes (Eircode) are alphanumeric and follow several formats, including Dublin postal districts (e.g., D6W).

---

#### Italy
##### Phone Number
- **Pattern:** `^\\+39[0-9]{6,12}$`
- **Description:** Matches Italian phone numbers, beginning with +39 and followed by 6 to 12 digits.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Matches Italian postal codes, which consist of 5 digits.

---

#### Latvia
##### Phone Number
- **Pattern:** `^\\+371[2-9][0-9]{7}$`
- **Description:** Latvian phone numbers begin with +371, followed by a digit between 2 
##### Postal Code
- **Pattern:** `^LV-\\d{4}$`
- **Description:** Latvian postal codes start with "LV-" followed by 4 digits.

---

#### Liechtenstein
##### Phone Number
- **Pattern:** `^\\+423[0-9]{3,12}$`
- **Description:** Liechtenstein phone numbers start with +423, followed by 3 to 12 digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Liechtenstein postal codes are made up of 4 digits.

---

#### Lithuania
##### Phone Number
- **Pattern:** `^\\+370[6-9][0-9]{7}$`
- **Description:** Lithuanian phone numbers start with +370, followed by a digit between 6 and 9, and then 7 more digits.
##### Postal Code
- **Pattern:** `^LT-\\d{5}$`
- **Description:** Lithuanian postal codes start with "LT-" followed by 5 digits.

---

#### Luxembourg
##### Phone Number
- **Pattern:** `^\\+352[0-9]{3,11}$`
- **Description:** Luxembourg phone numbers start with +352, followed by 3 to 11 digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Luxembourg postal codes consist of 4 digits.

---

#### Malta
##### Phone Number
- **Pattern:** `^\\+356[0-9]{8}$`
- **Description:** Malta phone numbers begin with +356, followed by 8 digits.
##### Postal Code
- **Pattern:** `^[A-Z]{3}\\s?\\d{2,4}$`
- **Description:** Maltese postal codes consist of three letters followed by a space (optional) and 2 to 4 digits.

---

#### Montenegro
##### Phone Number
- **Pattern:** `^\\+382[6-9][0-9]{6,7}$`
- **Description:** Montenegrin phone numbers typically start with +382, followed by a digit between 6 and 9, and then 6 to 7 more digits. This pattern covers both mobile and landline numbers.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Montenegrin postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.

---

#### Monaco
##### Phone Number
- **Pattern:** `^\\+377[0-9]{8,9}$`
- **Description:** Monaco phone numbers begin with +377, followed by 8 to 9 digits.
##### Postal Code
- **Pattern:** `^980\\d{2}$`
- **Description:** Monaco postal codes start with 980 followed by two additional digits.

---

#### Netherlands
##### Phone Number
- **Pattern:** `^\\+31[0-9]{9}$`
- **Description:** Matches Dutch phone numbers. Begins with +31 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^[1-9][0-9]{3}\\s?[A-Z]{2}$`
- **Description:** Matches Dutch postal codes, which consist of four digits followed by two letters.

---

#### North Macedonia
##### Phone Number
- **Pattern:** `^\\+389[2-9][0-9]{6,7}$`
- **Description:** North Macedonian phone numbers begin with +389, followed by a digit between 2 and 9, and then 6 to 7 additional digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** North Macedonian postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.

---

#### Norway
##### Phone Number
- **Pattern:** `^\\+47[2-9][0-9]{7,8}$`
- **Description:** Norwegian phone numbers begin with +47, followed by a digit between 2 and 9, and then 7 to 8 additional digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Norwegian postal codes consist of 4 digits.

---

#### Poland
##### Phone Number
- **Pattern:** `^\\+48[0-9]{9}$`
- **Description:** Matches Polish phone numbers, beginning with +48 and followed by 9 digits.
##### Postal Code
- **Pattern:** `^\\d{2}-\\d{3}$`
- **Description:** Matches Polish postal codes, which consist of two digits, a hyphen, and three more digits.

---

#### Portugal
##### Phone Number
- **Pattern:** `^\\+351[1-9][0-9]{8}$`
- **Description:** Matches Portuguese phone numbers. Begins with +351 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^\\d{4}-\\d{3}$`
- **Description:** Matches Portuguese postal codes, which consist of four digits, a hyphen, and three more digits.

---

#### Romania
##### Phone Number
- **Pattern:** `^\\+40[1-9][0-9]{8,9}$`
- **Description:** Romanian phone numbers start with +40, followed by a non-zero digit and 8 to 9 more digits.
##### Postal Code
- **Pattern:** `^\\d{6}$`
- **Description:** Romanian postal codes are made up of 6 digits.

---

#### San Marino
##### Phone Number
- **Pattern:** `^\\+378[0-9]{6,10}$`
- **Description:** San Marino phone numbers start with +378, followed by 6 to 10 digits.
##### Postal Code
- **Pattern:** `^4789\\d$`
- **Description:** San Marino postal codes are "4789" followed by one digit.

---

#### Serbia
##### Phone Number
- **Pattern:** `^\\+381[6-9][0-9]{6,8}$`
- **Description:** Serbian phone numbers start with +381, followed by a digit between 6 and 9, and then 6 to 8 more digits.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Serbian postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.

---

#### Slovakia
##### Phone Number
- **Pattern:** `^\\+421[1-9][0-9]{8}$`
- **Description:** Slovak phone numbers begin with +421, followed by a non-zero digit and 8 additional digits.
##### Postal Code
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Slovak postal codes have 5 digits, typically written with a space after the first three digits.

---

#### Slovenia
##### Phone Number
- **Pattern:** `^\\+386[1-9][0-9]{6,7}$`
- **Description:** Slovenian phone numbers start with +386, followed by a non-zero digit and 6 to 7 additional digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Slovenian postal codes consist of 4 digits.

---

#### Spain
##### Phone Number
- **Pattern:** `^\\+34[6-9][0-9]{8}$`
- **Description:** Matches Spanish phone numbers. Begins with +34, followed by a digit from 6 to 9, and then 8 more digits.
##### Postal Code
- **Pattern:** `^\\d{5}$`
- **Description:** Matches Spanish postal codes, which consist of 5 digits.

---

#### Sweden
##### Phone Number
- **Pattern:** `^\\+46[0-9]{7,13}$`
- **Description:** Matches Swedish phone numbers. Begins with +46 and is followed by 7 to 13 digits.
##### Postal Code
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Matches Swedish postal codes, consisting of three digits, an optional space, and two more digits.

---

#### Switzerland
##### Phone Number
- **Pattern:** `^\\+41[1-9][0-9]{8}$`
- **Description:** Swiss phone numbers begin with +41, followed by a non-zero digit and 8 additional digits.
##### Postal Code
- **Pattern:** `^\\d{4}$`
- **Description:** Swiss postal codes consist of 4 digits.

---

#### United Kingdom
##### Phone Number
- **Pattern:** `^\\+44[1-9][0-9]{9,10}$`
- **Description:** UK phone numbers start with +44, followed by a digit between 1 and 9, and then 9 to 10 additional digits. This pattern covers various formats including landlines, mobiles, and other services.
##### Postal Code
- **Pattern:** `^(GIR ?0AA|[A-Z]{1,2}[0-9]{1,2} ?[0-9][A-Z]{2})$`
- **Description:** Matches UK postal codes.

## Usage

### PHP

To use regex patterns in PHP, we can use the `preg_match` function.

Here's an example of how to validate a German phone number:

```php
$pattern = '/^\\+49[1-9][0-9]{1,14}$/';
$phoneNumber = '+491234567890';

if (preg_match($pattern, $phoneNumber)) {
    echo "Valid German phone number.";
} else {
    echo "Invalid German phone number.";
}
```
### Python

To use regex patterns in Python, we can use the `re` module, which provides support for regular expressions. 

Here's an example of how to validate a German phone number:

```python
import re

# Regex pattern for a German phone number
pattern = r'^\+49[1-9][0-9]{1,14}$'

# Sample German phone number to test
phone_number = '+491234567890'

# Using the re.match function to check if the pattern matches the phone number
if re.match(pattern, phone_number):
    print("Valid German phone number.")
else:
    print("Invalid German phone number.")
```

### C#

In C#, we can use the `System.Text.RegularExpressions` namespace to work with regex.

Here's an example of how to validate a German phone number:

```c
using System;
using System.Text.RegularExpressions;

class Program
{
    static void Main()
    {
        string pattern = @"^\+49[1-9][0-9]{1,14}$";
        string phoneNumber = "+491234567890";

        if (Regex.IsMatch(phoneNumber, pattern))
        {
            Console.WriteLine("Valid German phone number.");
        }
        else
        {
            Console.WriteLine("Invalid German phone number.");
        }
    }
}
```

### Java

In Java, regex functionalities are provided by the `java.util.regex` package.

Here's an example of how to validate a German phone number:

```java
import java.util.regex.Matcher;
import java.util.regex.Pattern;

public class Main {
    public static void main(String[] args) {
        String pattern = "^\\+49[1-9][0-9]{1,14}$";
        String phoneNumber = "+491234567890";

        Pattern r = Pattern.compile(pattern);
        Matcher m = r.matcher(phoneNumber);

        if (m.find()) {
            System.out.println("Valid German phone number.");
        } else {
            System.out.println("Invalid German phone number.");
        }
    }
}
```

### Ruby

Ruby has **built-in** support for regular expressions.

Here's an example of how to validate a German phone number:

```ruby
pattern = /^\+49[1-9][0-9]{1,14}$/
phone_number = "+491234567890"

if phone_number.match(pattern)
  puts "Valid German phone number."
else
  puts "Invalid German phone number."
end
```

### JavaScript

Here's an example of how to validate a German phone number:

```javascript
const pattern = /^\\+49[1-9][0-9]{1,14}$/;
const phoneNumber = '+491234567890';

if (pattern.test(phoneNumber)) {
    console.log("Valid German phone number.");
} else {
    console.log("Invalid German phone number.");
}
```

## :warning: Important :warning: 

The regex patterns provided here are examples and may not cover all cases or nuances of phone number and postal code formats. You would need to research and verify the patterns for each country. 

Also, remember that phone number and postal code formats can change, so it's good practice to periodically review and update these patterns.

---

## License

This repository is unlicense[d], so feel free to fork.
