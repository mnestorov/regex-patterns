# Regex Patterns for European Phone Numbers, Postal Codes, VAT Numbers, Dates, Currency etc.

![Licence](https://img.shields.io/badge/Unlicense-red)

## Overview

This repository contains regular expression (regex) patterns for validating phone numbers, postal codes, VAT numbers and some common and critical in various applications patterns like date, currency etc. for European countries. 

Below are the patterns for each European country, along with a brief description.

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
- [Common Patterns](#common-patterns)
  - [Dates](#dates)
  - [Currency](#currency)
  - [Vehicle Registration Codes](#vehicle-registration-codes)
  - [Credit and Debit Card Patterns](#credit-and-debit-card-patterns)
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
- **Pattern:** `^\+376[0-9]{6}$`
- **Description:** Andorran phone numbers start with +376, followed by 6 digits.
##### Postal Code
- **Pattern:** `^AD\d{3}$`
- **Description:** Andorran postal codes start with "AD" followed by 3 digits.
##### VAT Number
- Not applicable as Andorra does not have a standard VAT number system like EU countries.

---

#### Austria
##### Phone Number
- **Pattern:** `^\+43[1-9][0-9]{3,12}$`
- **Description:** Austrian phone numbers start with +43, followed by a non-zero digit and 3 to 12 more digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Austrian postal codes are made up of 4 digits.
##### VAT Number
- **Pattern:** `^ATU\d{8}$`
- **Description:** Austrian VAT numbers start with "ATU", followed by 8 digits.

---

#### Belgium
##### Phone Number
- **Pattern:** `^\+32[1-9][0-9]{7,8}$`
- **Description:** Belgian phone numbers typically start with +32, followed by a non-zero digit and then 7 to 8 additional digits. This pattern caters to both mobile and landline numbers.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Belgian postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.
##### VAT Number
- **Pattern:** `^BE0\d{9}$`
- **Description:** Belgian VAT numbers start with "BE0", followed by 9 digits.

---

#### Bosnia and Herzegovina
##### Phone Number
- **Pattern:** `^\+387[6][0-9]{7}$`
- **Description:** Bosnian phone numbers typically start with +387, followed by a 6 (indicating a mobile number) and then 7 more digits. This pattern is tailored towards mobile numbers, as they are the most commonly used.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Bosnian postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.
##### VAT Number
- Bosnia and Herzegovina does not have a VAT number system similar to that of the European Union. For business and tax purposes, companies use a national ID number system. It's essential to consult local regulations or authorities for accurate and specific requirements regarding tax identification and reporting in Bosnia and Herzegovina.

---

#### Bulgaria
##### Phone Number
- **Pattern:** `^\+359[1-9][0-9]{7,8}$`
- **Description:** Bulgarian phone numbers begin with +359, followed by a non-zero digit and 7 to 8 additional digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Bulgarian postal codes consist of 4 digits.
##### VAT Number
- **Pattern:** `BG\d{9,10}$`
- **Description:** Bulgarian VAT numbers start with "BG", followed by 9 or 10 digits.

---

#### Croatia
##### Phone Number
- **Pattern:** `^\+385[1-9][0-9]{7,8}$`
- **Description:** Croatian phone numbers start with +385, followed by a non-zero digit and 7 to 8 more digits.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Croatian postal codes are made up of 5 digits.
##### VAT Number
- **Pattern:** `^HR\d{11}$`
- **Description:** Croatian VAT numbers start with "HR", followed by 11 digits.

---

#### Cyprus
##### Phone Number
- **Pattern:** `^\+357[2-9][0-9]{6,7}$`
- **Description:** Cypriot phone numbers start with +357, followed by a digit between 2 and 9, and then 6 to 7 more digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Cypriot postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.
##### VAT Number
- **Pattern:** `^CY\d{8}L$`
- **Description:** Cypriot VAT numbers start with "CY", followed by 8 digits and a final letter.

---

#### Czech Republic
##### Phone Number
- **Pattern:** `^\+420[1-9][0-9]{8}$`
- **Description:** Matches Czech phone numbers. Begins with +420 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^\d{3}\s?\d{2}$`
- **Description:** Matches Czech postal codes, consisting of three digits, an optional space, and two more digits.
##### VAT Number
- **Pattern:** `^CZ\d{8,10}$`
- **Description:** Czech VAT numbers start with "CZ", followed by 8 to 10 digits.

---

#### Denmark
##### Phone Number
- **Pattern:** `^\+45[2-9][0-9]{7}$`
- **Description:** Danish phone numbers begin with +45, followed by a digit between 2 and 9, and then 7 more digits. This pattern covers the standard 8-digit format after the country code.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Danish postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.
##### VAT Number
- **Pattern:** `^DK\d{8}$`
- **Description:** Danish VAT numbers start with "DK", followed by 8 digits.

---

#### Estonia
##### Phone Number
- **Pattern:** `^\+372[5-9][0-9]{6,7}$`
- **Description:** Estonian phone numbers start with +372, followed by a digit between 5
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Estonian postal codes consist of 5 digits.
##### VAT Number
- **Pattern:** `^EE\d{9}$`
- **Description:** Estonian VAT numbers start with "EE", followed by 9 digits.

---

#### Finland
##### Phone Number
- **Pattern:** `^\+358[1-9][0-9]{4,11}$`
- **Description:** Finnish phone numbers start with +358, followed by a non-zero digit, and then 4 to 11 more digits.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Finnish postal codes consist of 5 digits.
##### VAT Number
- **Pattern:** `^FI\d{8}$`
- **Description:** Finnish VAT numbers start with "FI", followed by 8 digits.

---

#### France
##### Phone Number
- **Pattern:** `^\+33[1-9][0-9]{8}$`
- **Description:** Matches French phone numbers. Begins with +33 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** French postal codes are also 5 digits in length. This pattern matches a sequence of five numerical digits.
##### VAT Number
- **Pattern:** `^FR[A-HJ-NP-Z0-9]{2}\d{9}$`
- **Description:** French VAT numbers start with "FR", followed by two characters (either digits or letters except O and I) and then 9 digits.

---

#### Germany
##### Phone Number
- **Pattern:** `^\+49[1-9][0-9]{1,14}$`
- **Description:** Matches German phone numbers. Begins with +49 and is followed by 9 to 15 digits.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** German postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.
##### VAT Number
- **Pattern:** `^DE\d{9}$`
- **Description:** German VAT numbers start with "DE", followed by 9 digits.

---

#### Greece
##### Phone Number
- **Pattern:** `^\+30[2-9][0-9]{9}$`
- **Description:** Matches Greek phone numbers. Begins with +30, followed by a digit from 2 to 9, and then 9 more digits.
##### Postal Code
- **Pattern:** `^\d{3}\s?\d{2}$`
- **Description:** Matches Greek postal codes, consisting of three digits, an optional space, and two more digits.
##### VAT Number
- **Pattern:** `^EL\d{9}$`
- **Description:** Greek VAT numbers start with "EL", followed by 9 digits.

---

#### Hungary
##### Phone Number
- **Pattern:** `^\+36[1-9][0-9]{8}$`
- **Description:** Hungarian phone numbers begin with +36, followed by a non-zero digit and 8 additional digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Hungarian postal codes consist of 4 digits.
##### VAT Number
- **Pattern:** `^HU\d{8}$`
- **Description:** Hungarian VAT numbers start with "HU", followed by 8 digits.

---

#### Ireland
##### Phone Number
- **Pattern:** `^\+353[1-9][0-9]{6,9}$`
- **Description:** Irish phone numbers begin with +353, followed by a non-zero digit, and then 6 to 9 more digits.
##### Postal Code
- **Pattern:** `^(D6W|[A-Z]{1}[0-9]{1,2}|[A-Z]{2}[0-9]{1,2}|[A-Z]{1}[0-9]{1}[A-Z]{1}|[A-Z]{2}[0-9]{1}[A-Z]{1})$`
- **Description:** Irish postal codes (Eircode) are alphanumeric and follow several formats, including Dublin postal districts (e.g., D6W).
##### VAT Number
- **Pattern:** `^IE\d{7}[A-WY][A-I]?|IE[0-9+][A-Z+][0-9]{5}[A-WY]$`
- **Description:** Irish VAT numbers start with "IE", followed by 7 digits and one or two letters. Variants include an additional character before the last digit for newer numbers.

---

#### Italy
##### Phone Number
- **Pattern:** `^\+39[0-9]{6,12}$`
- **Description:** Matches Italian phone numbers, beginning with +39 and followed by 6 to 12 digits.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Matches Italian postal codes, which consist of 5 digits.
##### VAT Number
- **Pattern:** `^IT\d{11}$`
- **Description:** Italian VAT numbers start with "IT", followed by 11 digits.

---

#### Latvia
##### Phone Number
- **Pattern:** `^\+371[2-9][0-9]{7}$`
- **Description:** Latvian phone numbers begin with +371, followed by a digit between 2 
##### Postal Code
- **Pattern:** `^LV-\d{4}$`
- **Description:** Latvian postal codes start with "LV-" followed by 4 digits.
##### VAT Number
- **Pattern:** `^LV\d{11}$`
- **Description:** Latvian VAT numbers start with "LV", followed by 11 digits.

---

#### Liechtenstein
##### Phone Number
- **Pattern:** `^\+423[0-9]{3,12}$`
- **Description:** Liechtenstein phone numbers start with +423, followed by 3 to 12 digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Liechtenstein postal codes are made up of 4 digits.
##### VAT Number
- **Pattern:** `^LI\d{5}$`
- **Description:** Liechtenstein VAT numbers start with "LI", followed by 5 digits. The country uses a simpler system due to its smaller size.

---

#### Lithuania
##### Phone Number
- **Pattern:** `^\+370[6-9][0-9]{7}$`
- **Description:** Lithuanian phone numbers start with +370, followed by a digit between 6 and 9, and then 7 more digits.
##### Postal Code
- **Pattern:** `^LT-\d{5}$`
- **Description:** Lithuanian postal codes start with "LT-" followed by 5 digits.
##### VAT Number
- **Pattern:** `^LT\d{9,12}$`
- **Description:** Lithuanian VAT numbers start with "LT", followed by 9 or 12 digits.

---

#### Luxembourg
##### Phone Number
- **Pattern:** `^\+352[0-9]{3,11}$`
- **Description:** Luxembourg phone numbers start with +352, followed by 3 to 11 digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Luxembourg postal codes consist of 4 digits.
##### VAT Number
- **Pattern:** `^LU\d{8}$`
- **Description:** Luxembourg VAT numbers start with "LU", followed by 8 digits.

---

#### Malta
##### Phone Number
- **Pattern:** `^\+356[0-9]{8}$`
- **Description:** Malta phone numbers begin with +356, followed by 8 digits.
##### Postal Code
- **Pattern:** `^[A-Z]{3}\s?\d{2,4}$`
- **Description:** Maltese postal codes consist of three letters followed by a space (optional) and 2 to 4 digits.
##### VAT Number
- **Pattern:** `^MT\d{8}$`
- **Description:** Maltese VAT numbers start with "MT", followed by 8 digits.

---

#### Montenegro
##### Phone Number
- **Pattern:** `^\+382[6-9][0-9]{6,7}$`
- **Description:** Montenegrin phone numbers typically start with +382, followed by a digit between 6 and 9, and then 6 to 7 more digits. This pattern covers both mobile and landline numbers.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Montenegrin postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.
##### VAT Number
- **Pattern:** `^ME\d{8}$`
- **Description:** Montenegrin VAT numbers start with "ME", followed by 8 digits. Montenegro, not being an EU member, has its own VAT system.

---

#### Monaco
##### Phone Number
- **Pattern:** `^\+377[0-9]{8,9}$`
- **Description:** Monaco phone numbers begin with +377, followed by 8 to 9 digits.
##### Postal Code
- **Pattern:** `^980\d{2}$`
- **Description:** Monaco postal codes start with 980 followed by two additional digits.
##### VAT Number
- Monaco does not have a distinct VAT number system and uses the French VAT system. Businesses in Monaco typically use French VAT numbers, which start with "FR", followed by two characters (either digits or letters except O and I) and then 9 digits.
---

#### Netherlands
##### Phone Number
- **Pattern:** `^\+31[0-9]{9}$`
- **Description:** Matches Dutch phone numbers. Begins with +31 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^[1-9][0-9]{3}\s?[A-Z]{2}$`
- **Description:** Matches Dutch postal codes, which consist of four digits followed by two letters.
##### VAT Number
- **Pattern:** `^NL\d{9}B\d{2}$`
- **Description:** Dutch VAT numbers start with "NL", followed by 9 digits, "B", and 2 more digits.

---

#### North Macedonia
##### Phone Number
- **Pattern:** `^\+389[2-9][0-9]{6,7}$`
- **Description:** North Macedonian phone numbers begin with +389, followed by a digit between 2 and 9, and then 6 to 7 additional digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** North Macedonian postal codes consist of 4 digits. This pattern matches a sequence of exactly four numerical digits.
##### VAT Number
- **Pattern:** `^MK\d{13}$`
- **Description:** North Macedonian VAT numbers start with "MK", followed by 13 digits. This format reflects the country's specific tax identification system.

---

#### Norway
##### Phone Number
- **Pattern:** `^\+47[2-9][0-9]{7,8}$`
- **Description:** Norwegian phone numbers begin with +47, followed by a digit between 2 and 9, and then 7 to 8 additional digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Norwegian postal codes consist of 4 digits.
##### VAT Number
- **Pattern:** `^NO\d{9}MVA$`
- **Description:** Norwegian VAT numbers start with "NO", followed by 9 digits and end with "MVA" (which stands for "Merverdiavgift", the Norwegian term for VAT).

---

#### Poland
##### Phone Number
- **Pattern:** `^\+48[0-9]{9}$`
- **Description:** Matches Polish phone numbers, beginning with +48 and followed by 9 digits.
##### Postal Code
- **Pattern:** `^\d{2}-\d{3}$`
- **Description:** Matches Polish postal codes, which consist of two digits, a hyphen, and three more digits.
##### VAT Number
- **Pattern:** `^PL\d{10}$`
- **Description:** Polish VAT numbers start with "PL", followed by 10 digits.

---

#### Portugal
##### Phone Number
- **Pattern:** `^\+351[1-9][0-9]{8}$`
- **Description:** Matches Portuguese phone numbers. Begins with +351 and is followed by 9 digits.
##### Postal Code
- **Pattern:** `^\d{4}-\d{3}$`
- **Description:** Matches Portuguese postal codes, which consist of four digits, a hyphen, and three more digits.
##### VAT Number
- **Pattern:** `^PT\d{9}$`
- **Description:** Portuguese VAT numbers start with "PT", followed by 9 digits.

---

#### Romania
##### Phone Number
- **Pattern:** `^\+40[1-9][0-9]{8,9}$`
- **Description:** Romanian phone numbers start with +40, followed by a non-zero digit and 8 to 9 more digits.
##### Postal Code
- **Pattern:** `^\d{6}$`
- **Description:** Romanian postal codes are made up of 6 digits.
##### VAT Number
- **Pattern:** `^RO\d{2,10}$`
- **Description:** Romanian VAT numbers start with "RO", followed by between 2 and 10 digits.

---

#### San Marino
##### Phone Number
- **Pattern:** `^\+378[0-9]{6,10}$`
- **Description:** San Marino phone numbers start with +378, followed by 6 to 10 digits.
##### Postal Code
- **Pattern:** `^4789\d$`
- **Description:** San Marino postal codes are "4789" followed by one digit.
##### VAT Number
- **Pattern:** `^SM\d{5}$`
- **Description:** San Marino VAT numbers start with "SM", followed by 5 digits. Despite its size, San Marino has its own VAT system separate from Italy.

---

#### Serbia
##### Phone Number
- **Pattern:** `^\+381[6-9][0-9]{6,8}$`
- **Description:** Serbian phone numbers start with +381, followed by a digit between 6 and 9, and then 6 to 8 more digits.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Serbian postal codes consist of 5 digits. This pattern matches a sequence of exactly five numerical digits.
##### VAT Number
- **Pattern:** `^RS\d{9}$`
- **Description:** Serbian VAT numbers start with "RS", followed by 9 digits. Serbia, not being an EU member, has its own VAT registration system.

---

#### Slovakia
##### Phone Number
- **Pattern:** `^\+421[1-9][0-9]{8}$`
- **Description:** Slovak phone numbers begin with +421, followed by a non-zero digit and 8 additional digits.
##### Postal Code
- **Pattern:** `^\d{3}\s?\d{2}$`
- **Description:** Slovak postal codes have 5 digits, typically written with a space after the first three digits.
##### VAT Number
- **Pattern:** `^SK\d{10}$`
- **Description:** Slovak VAT numbers start with "SK", followed by 10 digits.

---

#### Slovenia
##### Phone Number
- **Pattern:** `^\+386[1-9][0-9]{6,7}$`
- **Description:** Slovenian phone numbers start with +386, followed by a non-zero digit and 6 to 7 additional digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Slovenian postal codes consist of 4 digits.
##### VAT Number
- **Pattern:** `^SI\d{8}$`
- **Description:** Slovenian VAT numbers start with "SI", followed by 8 digits.

---

#### Spain
##### Phone Number
- **Pattern:** `^\+34[6-9][0-9]{8}$`
- **Description:** Matches Spanish phone numbers. Begins with +34, followed by a digit from 6 to 9, and then 8 more digits.
##### Postal Code
- **Pattern:** `^\d{5}$`
- **Description:** Matches Spanish postal codes, which consist of 5 digits.
##### VAT Number
- **Pattern:** `^ES[A-Z]\d{7}[A-Z]$|^ES[A-Z][0-9]{7}[0-9A-Z]$|^ES[0-9]{8}[A-Z]$`
- **Description:** Spanish VAT numbers start with "ES", followed by various formats including a letter, 7 digits, then a letter; or 8 digits then a letter.

---

#### Sweden
##### Phone Number
- **Pattern:** `^\+46[0-9]{7,13}$`
- **Description:** Matches Swedish phone numbers. Begins with +46 and is followed by 7 to 13 digits.
##### Postal Code
- **Pattern:** `^\d{3}\s?\d{2}$`
- **Description:** Matches Swedish postal codes, consisting of three digits, an optional space, and two more digits.
##### VAT Number
- **Pattern:** `^SE\d{12}$`
- **Description:**  Swedish VAT numbers start with "SE", followed by 12 digits.

---

#### Switzerland
##### Phone Number
- **Pattern:** `^\+41[1-9][0-9]{8}$`
- **Description:** Swiss phone numbers begin with +41, followed by a non-zero digit and 8 additional digits.
##### Postal Code
- **Pattern:** `^\d{4}$`
- **Description:** Swiss postal codes consist of 4 digits.
##### VAT Number
- **Pattern:** `^CHE\d{9}MWST|TVA|IVA$`
- **Description:** Swiss VAT numbers start with "CHE", followed by 9 digits and end with "MWST", "TVA", or "IVA", depending on the language region (German, French, or Italian for VAT).

---

#### United Kingdom
##### Phone Number
- **Pattern:** `^\+44[1-9][0-9]{9,10}$`
- **Description:** UK phone numbers start with +44, followed by a digit between 1 and 9, and then 9 to 10 additional digits. This pattern covers various formats including landlines, mobiles, and other services.
##### Postal Code
- **Pattern:** `^(GIR ?0AA|[A-Z]{1,2}[0-9]{1,2} ?[0-9][A-Z]{2})$`
- **Description:** Matches UK postal codes.
##### VAT Number
- **Pattern:** `^GB\d{9}$|^GB\d{12}$|^GBGD\d{3}$|^GBHA\d{3}$`
- **Description:** UK VAT numbers start with "GB", followed by either 9 digits, 12 digits, or specific codes like "GD" or "HA" for government departments and health authorities, respectively. Despite Brexit, the UK continues to use a VAT system similar to that of the EU.

## Common Patterns

### Dates

European date formats typically use the day-month-year format, which differs from the month-day-year format used in the United States. 

A regex pattern to match this format can look like this: `^(0?[1-9]|[12][0-9]|3[01])/(0?[1-9]|1[012])/\d{4}$`

This pattern checks for a valid day (01 to 31), month (01 to 12), and a 4-digit year. The 0? allows for dates to be written with or without a leading zero (e.g., "1/1/2024" or "01/01/2024").

---

### Currency

To match amounts in euros, which might include commas for thousands separators and a period for the decimal point, you can use the following pattern: `^€\s?\d{1,3}(,\d{3})*(\.\d{2})?$`

This pattern supports amounts like "€1,000.00", "€100", and "€ 2,500.50". It ensures there is a euro symbol at the beginning, optional whitespace, followed by a number that may include commas and exactly two decimal places.

---

### Vehicle Registration Codes

Vehicle registration codes in Europe can vary, but a simple pattern to match a generic format might be: `^[A-Z]{1,3}-\d{1,4}-[A-Z]{1,3}$`

This pattern allows for 1 to 3 letters, followed by 1 to 4 digits, and then 1 to 3 letters again, all separated by dashes. This format matches some European vehicle registration codes but might need adjustments for specific countries.

---

### Credit and Debit Card Patterns

Below are regex patterns for various types of credit and debit cards. These patterns match the general format of card numbers issued by major card providers. 

**Keep in mind that these patterns only validate the format, not the actual validity of the card numbers.**

#### Visa
- **Pattern:** `^4[0-9]{12}(?:[0-9]{3})?$`
- **Description:** Visa cards start with a 4 and have either 13 or 16 digits.

#### MasterCard
- **Pattern:** `^5[1-5][0-9]{14}$`
- **Description:** MasterCard numbers start with digits 51 through 55 and have 16 digits.

#### American Express
- **Pattern:** `^3[47][0-9]{13}$`
- **Description:** American Express card numbers start with 34 or 37 and have 15 digits.

#### Discover
- **Pattern:** `^6(?:011|5[0-9]{2})[0-9]{12}$`
- **Description:** Discover cards start with 6011 or 65 and have 16 digits.

#### Diners Club
- **Pattern:** `^3(?:0[0-5]|[68][0-9])[0-9]{11}$`
- **Description:** Diners Club cards start with 300-305, 36, or 38 and have 14 digits.

#### JCB
- **Pattern:** `^(?:2131|1800|35\d{3})\d{11}$`
- **Description:** JCB cards start with 2131, 1800, or 35 and have 15 or 16 digits.

#### Maestro
- **Pattern:** `^(?:5[0678]\d{2}|6\d{3})\d{8,15}$`
- **Description:** Maestro cards have 12 to 19 digits and start with 50, 56-69.

#### UnionPay
- **Pattern:** `^62[0-9]{14,17}$`
- **Description:** UnionPay cards start with 62 and have 16 to 19 digits.

## Usage

### PHP

To use regex patterns in PHP, we can use the `preg_match` function.

Here's an example of how to validate a German phone number:

```php
$pattern = '/^\+49[1-9][0-9]{1,14}$/';
$phoneNumber = '+491234567890';

if (preg_match($pattern, $phoneNumber)) {
    echo "Valid German phone number.";
} else {
    echo "Invalid German phone number.";
}
```
Here's an example of how to validate a credit card number:

```php
$patterns = [
    'visa' => '/^4[0-9]{12}(?:[0-9]{3})?$/',
    'mastercard' => '/^5[1-5][0-9]{14}$/',
    'amex' => '/^3[47][0-9]{13}$/',
    'discover' => '/^6(?:011|5[0-9]{2})[0-9]{12}$/',
    'diners' => '/^3(?:0[0-5]|[68][0-9])[0-9]{11}$/',
    'jcb' => '/^(?:2131|1800|35\d{3})\d{11}$/',
    'maestro' => '/^(?:5[0678]\d{2}|6\d{3})\d{8,15}$/',
    'unionpay' => '/^62[0-9]{14,17}$/'
];

$cardNumber = '4111111111111111'; // example Visa card number

foreach ($patterns as $type => $pattern) {
    if (preg_match($pattern, $cardNumber)) {
        echo "Valid $type card number.";
        break;
    }
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

Here's an example of how to validate a credit card number:

```python
import re

patterns = {
    'visa': r'^4[0-9]{12}(?:[0-9]{3})?$',
    'mastercard': r'^5[1-5][0-9]{14}$',
    'amex': r'^3[47][0-9]{13}$',
    'discover': r'^6(?:011|5[0-9]{2})[0-9]{12}$',
    'diners': r'^3(?:0[0-5]|[68][0-9])[0-9]{11}$',
    'jcb': r'^(?:2131|1800|35\d{3})\d{11}$',
    'maestro': r'^(?:5[0678]\d{2}|6\d{3})\d{8,15}$',
    'unionpay': r'^62[0-9]{14,17}$'
}

card_number = '4111111111111111'  # example Visa card number

for card_type, pattern in patterns.items():
    if re.match(pattern, card_number):
        print(f"Valid {card_type} card number.")
        break
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
Here's an example of how to validate a credit card number:

```c
using System;
using System.Text.RegularExpressions;

class Program
{
    static void Main()
    {
        var patterns = new (string CardType, string Pattern)[]
        {
            ("Visa", @"^4[0-9]{12}(?:[0-9]{3})?$"),
            ("MasterCard", @"^5[1-5][0-9]{14}$"),
            ("Amex", @"^3[47][0-9]{13}$"),
            ("Discover", @"^6(?:011|5[0-9]{2})[0-9]{12}$"),
            ("Diners", @"^3(?:0[0-5]|[68][0-9])[0-9]{11}$"),
            ("JCB", @"^(?:2131|1800|35\d{3})\d{11}$"),
            ("Maestro", @"^(?:5[0678]\d{2}|6\d{3})\d{8,15}$"),
            ("UnionPay", @"^62[0-9]{14,17}$")
        };

        string cardNumber = "4111111111111111";  // example Visa card number

        foreach (var (CardType, Pattern) in patterns)
        {
            if (Regex.IsMatch(cardNumber, Pattern))
            {
                Console.WriteLine($"Valid {CardType} card number.");
                break;
            }
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
        String pattern = "^\+49[1-9][0-9]{1,14}$";
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

Here's an example of how to validate a credit card number:

```java
import java.util.regex.Matcher;
import java.util.regex.Pattern;

public class Main {
    public static void main(String[] args) {
        String[][] patterns = {
            {"Visa", "^4[0-9]{12}(?:[0-9]{3})?$"},
            {"MasterCard", "^5[1-5][0-9]{14}$"},
            {"Amex", "^3[47][0-9]{13}$"},
            {"Discover", "^6(?:011|5[0-9]{2})[0-9]{12}$"},
            {"Diners", "^3(?:0[0-5]|[68][0-9])[0-9]{11}$"},
            {"JCB", "^(?:2131|1800|35\\d{3})\\d{11}$"},
            {"Maestro", "^(?:5[0678]\\d{2}|6\\d{3})\\d{8,15}$"},
            {"UnionPay", "^62[0-9]{14,17}$"}
        };

        String cardNumber = "4111111111111111";  // example Visa card number

        for (String[] pattern : patterns) {
            Pattern r = Pattern.compile(pattern[1]);
            Matcher m = r.matcher(cardNumber);
            if (m.find()) {
                System.out.println("Valid " + pattern[0] + " card number.");
                break;
            }
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

Here's an example of how to validate a credit card number:

```ruby
patterns = {
  'visa' => /^4[0-9]{12}(?:[0-9]{3})?$/,
  'mastercard' => /^5[1-5][0-9]{14}$/,
  'amex' => /^3[47][0-9]{13}$/,
  'discover' => /^6(?:011|5[0-9]{2})[0-9]{12}$/,
  'diners' => /^3(?:0[0-5]|[68][0-9])[0-9]{11}$/,
  'jcb' => /^(?:2131|1800|35\d{3})\d{11}$/,
  'maestro' => /^(?:5[0678]\d{2}|6\d{3})\d{8,15}$/,
  'unionpay' => /^62[0-9]{14,17}$/
}

card_number = "4111111111111111" # example Visa card number

patterns.each do |type, pattern|
  if card_number.match(pattern)
    puts "Valid #{type} card number."
    break
  end
end
```

### JavaScript

Here's an example of how to validate a German phone number:

```javascript
const pattern = /^\+49[1-9][0-9]{1,14}$/;
const phoneNumber = '+491234567890';

if (pattern.test(phoneNumber)) {
    console.log("Valid German phone number.");
} else {
    console.log("Invalid German phone number.");
}
```
Here's an example of how to validate a credit card number:

```javascript
const patterns = {
    visa: /^4[0-9]{12}(?:[0-9]{3})?$/,
    mastercard: /^5[1-5][0-9]{14}$/,
    amex: /^3[47][0-9]{13}$/,
    discover: /^6(?:011|5[0-9]{2})[0-9]{12}$/,
    diners: /^3(?:0[0-5]|[68][0-9])[0-9]{11}$/,
    jcb: /^(?:2131|1800|35\d{3})\d{11}$/,
    maestro: /^(?:5[0678]\d{2}|6\d{3})\d{8,15}$/,
    unionpay: /^62[0-9]{14,17}$/
};

const cardNumber = '4111111111111111';  // example Visa card number

for (let type in patterns) {
    if (patterns[type].test(cardNumber)) {
        console.log(`Valid ${type} card number.`);
        break;
    }
}
```

## :warning: Important :warning: 

The regex patterns provided here are examples and may not cover all cases or nuances of phone number, postal code, VAT number and vehicle registration code formats. You would need to research and verify the patterns for each country. 

Also, remember that phone number, postal code, VAT number and vehicle registration code formats can change, so it's good practice to periodically review and update these patterns.

Be sure to test thoroughly and adjust the patterns as necessary to fit your specific requirements.

## Thank You

Every contribution helps. If you have any questions, feel free to reach out.

---

## License

This repository is unlicense[d], so feel free to fork.
