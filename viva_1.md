### **Question 1: City Name Extraction and Address Processing**

**Problem:**

You are given an address and a city name. Your task is to extract the city name from the address if it is present, and remove it from the address. You also need to remove special characters from the address, keeping only alphanumeric characters.

**Input:**
- **Address:** `123 Elm Street, Springfield`
- **City:** `Springfield`

**Output:**
- **Modified Address (without city):** The address with the city name removed and special characters (e.g., whitespace, commas) removed.
- **Reversed City Name:** The reversed city name.

**Sample Output:**
- **Modified Address (without city):** `123 Elm Street`
- **Reversed City Name:** `dleifgnirps`

### **Question 2: Character Replacement and Date of Birth Processing**

**Problem:**

You are given an address and a birth date in the format `dd mm yyyy`. Perform the following tasks:
1. Replace each vowel in the address with the next consonant and each consonant with the next vowel.
2. Determine the next prime number greater than the given day (`dd`). If the day is 30 or 31, adjust according to the month.
3. Check if the year (`yyyy`) is an Armstrong number.
4. Check if the concatenation of `ddmmyyyy` forms a palindrome.

**Input:**
- **Address:** `123 Elm Street`
- **Birth Date:** `15 08 1990`

**Output:**
- **Address with Replaced Characters:** The address with vowels replaced by the next consonant and consonants replaced by the next vowel.
- **Next Prime Day:** The next prime number greater than `dd`.
- **Year Armstrong Check:** `True` if `yyyy` is an Armstrong number, otherwise `False`.
- **Palindrome Check:** `True` if `ddmmyyyy` is a palindrome, otherwise `False`.

**Sample Output:**
- **Address with Replaced Characters:** `123 Foo Uuuffu`
- **Next Prime Day:** `17`
- **Year Armstrong Check:** `False`
- **Palindrome Check:** `False`

### **Question 3: Address and City Analysis**

**Problem:**

Given the processed address and city name, perform the following tasks:
1. Count the number of alphanumeric characters in the processed address.
2. Identify characters or numbers appearing in the city name, birth date, and address, and store them in a list.
3. Calculate the sum of the digits of the year (`yyyy`). Check if both `yyyy` and `ddmmyyyy` are divisible by this sum.

**Input:**
- **Processed Address:** `123 Elm Street`
- **City Name:** `Springfield`
- **Birth Date:** `15 08 1990`

**Output:**
- **Alphanumeric Character Count:** The count of alphanumeric characters in the processed address.
- **Common Characters:** List of characters or numbers appearing in the city name, birth date, and address.
- **Sum of Year Digits:** The sum of the digits of the year (`yyyy`).
- **Divisibility Check:** `True` if both `yyyy` and `ddmmyyyy` are divisible by the sum of the year digits, otherwise `False`.

**Sample Output:**
- **Alphanumeric Character Count:** `12`
- **Common Characters:** `1`, `2`, `3`, `5`
- **Sum of Year Digits:** `19`
- **Divisibility Check:** `False`

    ### Note: Check if the date of birth is valid.
