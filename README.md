# GENERATE-OTP-USING-PYTHON

import random

otp = random.randint(100,9999)
print(otp)

user = int(input('Enter OTP: '))
if user == otp:
    print('Access Granted :)')
else:
    print('Access Denied')
