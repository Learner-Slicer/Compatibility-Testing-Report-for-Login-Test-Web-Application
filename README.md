# Compatibility Testing – Task 4

## Overview:
For Task 4 of my internship at Prodigy InfoTech, I performed compatibility testing on the same login page I created for Task 3. The purpose was to check how the page looks and works on different browsers and screen sizes.

## Browsers and Devices Tested:
- Microsoft Edge (Desktop)
- Google Chrome (Desktop + Mobile View)
- Mozilla Firefox (Desktop)
- Safari (iPhone – real device)

## What I Tested:
### Layout:
- On Edge and Chrome desktop, everything looked centered and fine.
- On Firefox, the green login button looked slightly different in shade.
- On Safari (iPhone), the text and input fields appeared small.
- On Chrome mobile view, the blue box with usernames and password went off the screen.

### Functionality:
- Login button worked in all browsers.
- Redirection to Flipkart worked when valid credentials were used.
- Leaving username and password empty kept the user on the same page, which is expected.

### Links:
- The redirection link to Flipkart worked in all cases after successful login.

## Issues Found:
- Input fields and text were a bit too small on mobile devices.
- The layout was not responsive on smaller screens like phones.
- Firefox showed the login button in a slightly duller color than other browsers.

## Fixes I Recommend:
- Add responsive CSS using media queries for mobile layout.
- Use larger font sizes and input fields for mobile view.
- Check color styles and use more consistent color codes for buttons.
- Add a viewport meta tag to help with mobile scaling.

## Conclusion:
The login page worked well on all browsers, with only small issues on mobile screens. A few CSS changes can improve the mobile experience and make the page fully responsive.

## Author:
# Rathun Rajeevan  
BCA Student – Jain (Deemed-to-be) University  
Software Testing Intern – Prodigy InfoTech
