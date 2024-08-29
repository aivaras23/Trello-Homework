# Registration Form Manual Test Cases

## 1. Form Field Validation

### Test Case 1: Required Fields

## Requirements: Ensure that all form fields are required.

**Steps**:

1. Attempt to submit the form without filling out any fields.
2. Check if the form does not submit and that validation messages are shown for each required field.

**Expected Result**: Form submission should be blocked, and validation messages should appear next to each empty field.

# First name field functionality

## Filling the field

### First name taped correctly

**Requirements**

1. Text should be added without page reload
1. Starts with capital letter
1. Length should be at least 1 symbol (letter)
1. Input only in Latin
1. No special symbols or/and numbers
1. Space only between words
1. Can be consist of several words

**Steps**

- Open internet page
- Tap first name according to the requirements

**Expected results**

- No error found
- First name field stay filled

### Some mistake in first name

**Steps**

- Tap first name with number symbol

**Expected results**

- Error message appears and registration can not be finished

# Last name field functionality

## Filling the field

### Last name added correctly

**Requirements**

1. Text should be added without page reload
1. Starts with capital letter
1. Length should be at least 1 symbol (letter)
1. Input only in Latin
1. No special symbols or/and numbers

**Steps**

- Tap Last name according to the requirements

**Expected results**

- No error found
- Last name field stay filled

### Some mistake in Last name

**Steps**

- Tap Last name in Cyrillic

**Expected results**

- Error message appears and registration can not be fnished

# Email field functionality

## Filling the field

### Email taped correctly

**Requirements**

1. Text should be added without page reload
1. Should contain an "@" symbol and a domain name
1. Should not contain spaces
1. Should have valid format (e.g 'user@gmail.com, user@yandex.ru)
1. Should not start or end with special characters (e.g ".", "-", "\_", "$", etc.)
1. Field can not be left empty
1. Input only in Latin

**Steps**

- Tap email according to the requirements

**Expected results**

- No error found
- Email field stay filled

### Some mistake in Email

**Steps**

- Tap invalid email format: user@zef2

**Expected results**

- Error message appears and registration can not be finished

# Password field functionality

## Filling the field

### Password taped correctly

**Requirements**

1. Text should be added without page reload
1. Should be at least 8 characters long
1. Should contain at least one uppercase letter
1. Should contain at least one lowercase letter
1. Should contain at least one digit
1. Should contain at least one special character (e.g "@", "#", "$", etc.)
1. Should not contain spaces
1. Should not be too common or easily guessable like "123456"
1. Input in different languages is accepted
1. Field can not be left empty

**Steps**

- Tap password according to the requirements

**Expected results**

- No error found
- Password field stay filled, all written text is hidden behind "\*" symbols

### Some mistake in Password

**Steps**

- Tap password without a digit

**Expected results**

- Error message appears and registration can not be finished

# Confirm Password field functionality

## Filling the field

### Password's copy taped correctly

**Requirements**

1. Confirm Password should exactly match the Password field

**Steps**

- Tap copy of the password

**Expected results**

- No error found
- Confirm Password field stay filled, all written text is hidden behind "\*" symbols

### Passwords do not match

**Steps**

- Tap diffent password

**Expected results**

- Error message appears and registration can not be finished
