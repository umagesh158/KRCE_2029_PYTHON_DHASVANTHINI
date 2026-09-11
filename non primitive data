# Q1. Username Initializer
username = input()
print(username[0].upper())


# Q2. Notification Cleaner
message = input()
print(message.strip())


# Q3. OTP Validator
otp = input()

if len(otp) == 6 and otp.isdigit():
    print("Valid OTP")
else:
    print("Invalid OTP")


# Q4. Domain Detector
email = input()

if email.endswith("@gmail.com"):
    print("Gmail")
else:
    print("Other")


# Q5. Search Keyword
title = input()

if "phone" in title.lower():
    print("Match")
else:
    print("No Match")


# Q6. Username Normalizer
username = input()
username = username.strip().lower()
username = username.replace(" ", "_")
print(username)


# Q7. Secret Code Extractor
code = input()
parts = code.split("-")
print(parts[-1])


# Q8. Smart Email Masker
email = input()

pos = email.find("@")
name = email[:pos]
domain = email[pos:]

masked = name[0] + "*" * (len(name) - 2) + name[-1]

print(masked + domain)


# Q9. Duplicate Character Detector
message = input().lower()

found = False

for ch in message:
    if ch != " " and message.count(ch) > 1:
        found = True
        break

if found:
    print("Duplicate Found")
else:
    print("No Duplicate")


# Q10. Hashtag Generator
sentence = input()

words = sentence.strip().split()
hashtag = "#" + "".join(word.title() for word in words)

print(hashtag)


# Q11. Password Strength Scanner
password = input()

has_upper = any(ch.isupper() for ch in password)
has_lower = any(ch.islower() for ch in password)
has_digit = any(ch.isdigit() for ch in password)

if len(password) >= 8 and has_upper and has_lower and has_digit:
    print("Strong")
elif len(password) >= 6 and (has_digit or has_upper):
    print("Medium")
else:
    print("Weak")


# Q12. Log Error Scanner
.
log = input().lower()

print(log.count("error"))


# Q13. Message Compression
message = input()

# split() removes extra spaces between words
# join() joins them using a single space
print(" ".join(message.split()))


# Q14. Hidden Word Detector
sentence = input()

words = sentence.lower().split()

if "dragon" in words:
    print("FOUND")
else:
    print("NOT FOUND")


# Q15. Smart Palindrome Checker
text = input()

# Keep only letters and numbers
cleaned = ""

for ch in text:
    if ch.isalnum():
        cleaned += ch.lower()

# Check palindrome
if cleaned == cleaned[::-1]:
    print("Palindrome")
else:
    print("Not Palindrome")
