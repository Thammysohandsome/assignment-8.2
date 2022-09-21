SEND 'Enter your height (in metres).' TO DISPLAY
RECEIVE height FROM KEYBOARD
SEND 'Enter your weight (in kilograms).' TO DISPLAY
RECEIVE weight FROM KEYBOARD 
SET BMI TO weight/height^2
SEND 'Your body mass index is.' BMI TO DISPLAY
