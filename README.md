# European Phone Numbers and Postal Codes Regex Patterns

This repository contains regular expression (regex) patterns for validating phone numbers and postal codes for European countries. 

Below are the patterns for each country, along with a brief description.

## Contents
- [Regex Patterns](#regex-patterns)
  - [Phone Numbers](#phone-numbers)
  - [Postal Codes](#postal-codes)
- [Usage](#usage)
  - [PHP](#php)
  - [JavaScript](#javascript)

## Regex Patterns

### Phone Numbers

#### 🇦🇩 Andorra
- **Pattern:** `^\\+376[0-9]{6}$`
- **Description:** Andorran phone numbers start with +376, followed by 6 digits.

#### 🇦🇹 Austria
- **Pattern:** `^\\+43[1-9][0-9]{3,12}$`
- **Description:** Austrian phone numbers start with +43, followed by a non-zero digit and 3 to 12 more digits.

#### 🇧🇬 Bulgaria
- **Pattern:** `^\\+359[1-9][0-9]{7,8}$`
- **Description:** Bulgarian phone numbers begin with +359, followed by a non-zero digit and 7 to 8 additional digits.

#### 🇭🇷 Croatia
- **Pattern:** `^\\+385[1-9][0-9]{7,8}$`
- **Description:** Croatian phone numbers start with +385, followed by a non-zero digit and 7 to 8 more digits.

#### 🇨🇿 Czech Republic
- **Pattern:** `^\\+420[1-9][0-9]{8}$`
- **Description:** Matches Czech phone numbers. Begins with +420 and is followed by 9 digits.

#### 🇫🇷 France
- **Pattern:** `^\\+33[1-9][0-9]{8}$`
- **Description:** Matches French phone numbers. Begins with +33 and is followed by 9 digits.
- 
#### 🇩🇪 Germany
- **Pattern:** `^\\+49[1-9][0-9]{1,14}$`
- **Description:** Matches German phone numbers. Begins with +49 and is followed by 9 to 15 digits.

#### 🇬🇷 Greece
- **Pattern:** `^\\+30[2-9][0-9]{9}$`
- **Description:** Matches Greek phone numbers. Begins with +30, followed by a digit from 2 to 9, and then 9 more digits.

#### 🇭🇺 Hungary
- **Pattern:** `^\\+36[1-9][0-9]{8}$`
- **Description:** Hungarian phone numbers begin with +36, followed by a non-zero digit and 8 additional digits.

#### 🇮🇹 Italy
- **Pattern:** `^\\+39[0-9]{6,12}$`
- **Description:** Matches Italian phone numbers, beginning with +39 and followed by 6 to 12 digits.

#### 🇱🇮 Liechtenstein
- **Pattern:** `^\\+423[0-9]{3,12}$`
- **Description:** Liechtenstein phone numbers start with +423, followed by 3 to 12 digits.

#### 🇱🇺 Luxembourg
- **Pattern:** `^\\+352[0-9]{3,11}$`
- **Description:** Luxembourg phone numbers start with +352, followed by 3 to 11 digits.

#### 🇲🇹 Malta
- **Pattern:** `^\\+356[0-9]{8}$`
- **Description:** Malta phone numbers begin with +356, followed by 8 digits.

#### 🇲🇨 Monaco
- **Pattern:** `^\\+377[0-9]{8,9}$`
- **Description:** Monaco phone numbers begin with +377, followed by 8 to 9 digits.

#### 🇳🇱 Netherlands
- **Pattern:** `^\\+31[0-9]{9}$`
- **Description:** Matches Dutch phone numbers. Begins with +31 and is followed by 9 digits.

#### 🇵🇱 Poland
- **Pattern:** `^\\+48[0-9]{9}$`
- **Description:** Matches Polish phone numbers, beginning with +48 and followed by 9 digits.

#### 🇵🇹 Portugal
- **Pattern:** `^\\+351[1-9][0-9]{8}$`
- **Description:** Matches Portuguese phone numbers. Begins with +351 and is followed by 9 digits.

#### 🇷🇴 Romania
- **Pattern:** `^\\+40[1-9][0-9]{8,9}$`
- **Description:** Romanian phone numbers start with +40, followed by a non-zero digit and 8 to 9 more digits.

#### 🇸🇲 San Marino
- **Pattern:** `^\\+378[0-9]{6,10}$`
- **Description:** San Marino phone numbers start with +378, followed by 6 to 10 digits.

#### 🇸🇰 Slovakia
- **Pattern:** `^\\+421[1-9][0-9]{8}$`
- **Description:** Slovak phone numbers begin with +421, followed by a non-zero digit and 8 additional digits.

#### 🇸🇮 Slovenia
- **Pattern:** `^\\+386[1-9][0-9]{6,7}$`
- **Description:** Slovenian phone numbers start with +386, followed by a non-zero digit and 6 to 7 additional digits.

#### 🇪🇸 Spain
- **Pattern:** `^\\+34[6-9][0-9]{8}$`
- **Description:** Matches Spanish phone numbers. Begins with +34, followed by a digit from 6 to 9, and then 8 more digits.

#### 🇸🇪 Sweden
- **Pattern:** `^\\+46[0-9]{7,13}$`
- **Description:** Matches Swedish phone numbers. Begins with +46 and is followed by 7 to 13 digits.

#### 🇨🇭 Switzerland
- **Pattern:** `^\\+41[1-9][0-9]{8}$`
- **Description:** Swiss phone numbers begin with +41, followed by a non-zero digit and 8 additional digits.

#### 🇬🇧 United Kingdom
- **Pattern:** `^\\+44[1-9][0-9]{9,10}$`
- **Description:** UK phone numbers start with +44, followed by a digit between 1 and 9, and then 9 to 10 additional digits. This pattern covers various formats including landlines, mobiles, and other services.
  
### Postal Codes

#### 🇦🇩 Andorra
- **Pattern:** `^AD\\d{3}$`
- **Description:** Andorran postal codes start with "AD" followed by 3 digits.

#### 🇦🇹 Austria
- **Pattern:** `^\\d{4}$`
- **Description:** Austrian postal codes are made up of 4 digits.

#### 🇧🇬 Bulgaria
- **Pattern:** `^\\d{4}$`
- **Description:** Bulgarian postal codes consist of 4 digits.

#### 🇭🇷 Croatia
- **Pattern:** `^\\d{5}$`
- **Description:** Croatian postal codes are made up of 5 digits.

#### 🇨🇿 Czech Republic
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Matches Czech postal codes, consisting of three digits, an optional space, and two more digits.

#### 🇫🇷 France
- **Pattern:** `^\\d{5}$`
- **Description:** French postal codes are also 5 digits in length. This pattern matches a sequence of five numerical digits.

#### 🇩🇪 Germany
- **Pattern:** `^\\d{5}$`
- **Description:** German postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.

#### 🇬🇷 Greece
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Matches Greek postal codes, consisting of three digits, an optional space, and two more digits.

#### 🇭🇺 Hungary
- **Pattern:** `^\\d{4}$`
- **Description:** Hungarian postal codes consist of 4 digits.

#### 🇮🇹 Italy
- **Pattern:** `^\\d{5}$`
- **Description:** Matches Italian postal codes, which consist of 5 digits.

#### 🇱🇮 Liechtenstein
- **Pattern:** `^\\d{4}$`
- **Description:** Liechtenstein postal codes are made up of 4 digits.

#### 🇱🇺 Luxembourg
- **Pattern:** `^\\d{4}$`
- **Description:** Luxembourg postal codes consist of 4 digits.

#### 🇲🇹 Malta
- **Pattern:** `^[A-Z]{3}\\s?\\d{2,4}$`
- **Description:** Maltese postal codes consist of three letters followed by a space (optional) and 2 to 4 digits.

#### 🇲🇨 Monaco
- **Pattern:** `^980\\d{2}$`
- **Description:** Monaco postal codes start with 980 followed by two additional digits.

#### 🇳🇱 Netherlands
- **Pattern:** `^[1-9][0-9]{3}\\s?[A-Z]{2}$`
- **Description:** Matches Dutch postal codes, which consist of four digits followed by two letters.

#### 🇵🇱 Poland
- **Pattern:** `^\\d{2}-\\d{3}$`
- **Description:** Matches Polish postal codes, which consist of two digits, a hyphen, and three more digits.

#### 🇵🇹 Portugal
- **Pattern:** `^\\d{4}-\\d{3}$`
- **Description:** Matches Portuguese postal codes, which consist of four digits, a hyphen, and three more digits.

#### 🇷🇴 Romania
- **Pattern:** `^\\d{6}$`
- **Description:** Romanian postal codes are made up of 6 digits.

#### 🇸🇲 San Marino
- **Pattern:** `^4789\\d$`
- **Description:** San Marino postal codes are "4789" followed by one digit.

#### 🇸🇰 Slovakia
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Slovak postal codes have 5 digits, typically written with a space after the first three digits.

#### 🇸🇮 Slovenia
- **Pattern:** `^\\d{4}$`
- **Description:** Slovenian postal codes consist of 4 digits.

#### 🇪🇸 Spain
- **Pattern:** `^\\d{5}$`
- **Description:** Matches Spanish postal codes, which consist of 5 digits.

#### 🇸🇪 Sweden
- **Pattern:** `^\\d{3}\\s?\\d{2}$`
- **Description:** Matches Swedish postal codes, consisting of three digits, an optional space, and two more digits.

#### 🇨🇭 Switzerland
- **Pattern:** `^\\d{4}$`
- **Description:** Swiss postal codes consist of 4 digits.

#### 🇬🇧 United Kingdom
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

## Important

The regex patterns provided here are examples and may not cover all cases or nuances of phone number and postal code formats. You would need to research and verify the patterns for each country. Also, remember that phone number and postal code formats can change, so it's good practice to periodically review and update these patterns.

---

## License

This project is released under the MIT License.
