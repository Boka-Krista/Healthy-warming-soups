# Testing




Throughout my project I kept testing my code in https://validator.w3.org and tried to fix any possible errors right away. At the same time while working on it, at all times I had preview (python3 -m http.server) opened to see if all navbar buttons are responsive and if added links are working as supposed to like opening in new tab etc.


## Code Validation

At first I validated each page separately, which all passed and is seen in documentation folder.

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.


| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups%2Findex.html) | ![screenshot](documentation/TESTING.md/index.png) | Pass: No Errors |
| About | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups%2Fabout.html) | ![screenshot](documentation/TESTING.md/about.png) | Pass: No Errors |
| Borsch | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups%2Fborsch.html) | ![screenshot](documentation/TESTING.md/borsch.png) | Pass: No Errors |
| Split peas soup | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups%2Fsplit-peas-soup.html) | ![screenshot](documentation/TESTING.md/split-peas-soup.png) | Pass: No Errors |
| Souerkraut soup | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups%2Fsouerkraut-soup.html) | ![screenshot](documentation/TESTING.md/souerkraut.png) | Pass: No Errors |
| Sign up | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups%2Fsign-up.html) | ![screenshot](documentation/TESTING.md/sign-up.png) |  Pass: No Errors|
| Thank you | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups%2Fthank-you.html) | ![screenshot](documentation/TESTING.md/thank-you.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.


| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2FBoka-Krista.github.io%2FHealthy-warming-soups) | ![screenshot](documentation/TESTING.md/css.png) | Pass: No Errors |


## Browser Compatibility


Recommended browsers to consider:
- [Chrome](https://www.google.com/chrome)
- [Firefox](https://www.mozilla.org/firefox)
- [Safari](https://support.apple.com/downloads/safari)



I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | About | Split peas soup | Borsch |  Souerkraut soup | Sign up | Thank you note| Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/TESTING.md/google-chrome.png)| ![screenshot](documentation/TESTING.md/chrome-about.png) | ![screenshot](documentation/TESTING.md/chrome-split-peas.png) | ![screenshot](documentation/TESTING.md/chrome-borsch.png) | |![screenshot](documentation/TESTING.md/chrome-souerkraut-soup.png) |  ![screenshot](documentation/TESTING.md/chrome-sign-up.png) | ![screenshot](documentation/TESTING.md/chrome-thank-you.png) | Works as expected |
| Firefox | ![screenshot](documentation/TESTING.md/firefox.png) | ![screenshot](documentation/TESTING.md/firefox-about.png) | ![screenshot](documentation/TESTING.md/firefox-split-peas-soup.png) | ![screenshot](documentation/TESTING.md/firefox-borsch.png) |![screenshot](documentation/TESTING.md/firefox-souerkraut-soup.png) |![screenshot](documentation/TESTING.md/firefox-sign-up.png) |![screenshot](documentation/TESTING.md/firefox-thank-you.png) | Works as expected |
| Safari | ![screenshot](documentation/TESTING.md/safari.png) | ![screenshot](documentation/TESTING.md/safari-about.png) | ![screenshot](documentation/TESTING.md/safari-split-peas.png) | ![screenshot](documentation/TESTING.md/safari-borsch.png)![screenshot](documentation/TESTING.md/safari-souerkraut.png) |![screenshot](documentation/TESTING.md/safari-sign-up.png) | ![screenshot](documentation/TESTING.md/safari-thank-you.png) | Minor CSS differences |

## Responsiveness



| Device | Home | About | Sauerkraut soup | Borsch | Split peas soup | Sign up | Thank you note | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/TESTING.md/mobile-home.png) | ![screenshot](documentation/TESTING.md/mobile-about.png) | ![screenshot](documentation/TESTING.md/mobile-souerkraut.png) | ![screenshot](documentation/TESTING.md/mobile-borsch.png) |![screenshot](documentation/TESTING.md/mobile-split-peas.png) | ![screenshot](documentation/TESTING.md/mobile-signup.png) |![screenshot](documentation/TESTING.md/mobile-thankyou.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/TESTING.md/tablet-home.png) | ![screenshot](documentation/TESTING.md/tablet-about.png) | ![screenshot](documentation/TESTING.md/tablet-souerkraut.png) | ![screenshot](documentation/TESTING.md/tablet-borsch.png) |![screenshot](documentation/TESTING.md/tablet-split-peas.png) |![screenshot](documentation/TESTING.md/tablet-signup.png) |![screenshot](documentation/TESTING.md/tablet-thankyou.png) | Works as expected |
| Desktop | ![screenshot](documentation/TESTING.md/google-chrome.png) | ![screenshot](documentation/TESTING.md/chrome-about.png) | ![screenshot](documentation/TESTING.md/chrome-souerkraut-soup.png) | ![screenshot](documentation/TESTING.md/chrome-borsch.png) |![screenshot](documentation/TESTING.md/chrome-split-peas.png) |![screenshot](documentation/TESTING.md/chrome-sign-up.png) |![screenshot](documentation/TESTING.md/chrome-thank-you.png) | Works as expected |
| XL Monitor | ![screenshot](documentation/TESTING.md/xl-home.png) | ![screenshot](documentation/TESTING.md/xl-about.png) | ![screenshot](documentation/TESTING.md/xl-souerkraut.png) | ![screenshot](documentation/TESTING.md/xl-borsch.png) | ![screenshot](documentation/TESTING.md/xl-split-peas.png) |![screenshot](documentation/TESTING.md/xl-signup.png) |![screenshot](documentation/TESTING.md/xl-thank-you.png) | Scaling starts to stretch |
| 4K Monitor | ![screenshot](documentation/TESTING.md/4K-home.png) | ![screenshot](documentation/TESTING.md/4K-about.png) | ![screenshot](documentation/TESTING.md/4K-soerkraut.png) | ![screenshot](documentation/TESTING.md/4K-borsch.png) |![screenshot](documentation/TESTING.md/4K-split-peas.png) |![screenshot](documentation/TESTING.md/4K-signup.png) |![screenshot](documentation/TESTING.md/4K-thsnkyou.png) | Noticeable scaling issues |
| Google Pixel 7 Pro | ![screenshot](documentation/TESTING.md/pixel7pro-home.png) | ![screenshot](documentation/TESTING.md/pixel7pro-about.png) | ![screenshot](documentation/TESTING.md/pixel7pro-souerkraut.png) | ![screenshot](documentation/TESTING.md/pixel7pro-borsch.png) |![screenshot](documentation/TESTING.md/pixel7pro-split-peas.png) |![screenshot](documentation/TESTING.md/pixel7pro-signup.png) |![screenshot](documentation/TESTING.md/pixel7pro-thankyou.png) | Works as expected |
| iPhone 14 | ![screenshot](documentation/TESTING.md/iphone-home.png) | ![screenshot](documentation/TESTING.md/iphone-about.png) | ![screenshot](documentation/TESTING.md/iphone-souerkraut.png) | ![screenshot](documentation/TESTING.md/iphone-borsch.png) |![screenshot](documentation/TESTING.md/iphone-split-peas.png) |![screenshot](documentation/TESTING.md/iphone-signup.png) |![screenshot](documentation/TESTING.md/iphone-thankyou.png) | Works as expected |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- | 
| Home | ![screenshot](documentation/TESTING.md/lighthouse-mobile-home.png) | ![screenshot](documentation/TESTING.md/lighthouse-desktop-home.png) | Some minor warnings |
| About | ![screenshot](documentation/TESTING.md/lighthouse-mobile-about.png) | ![screenshot](documentation/TESTING.md/lighthouse-desktop-about.png) | Some minor warnings |
| Borsch| ![screenshot](documentation/TESTING.md/lighthouse-mobile-borsch.png) | ![screenshot](documentation/TESTING.md/lighthouse-desktop-borsch.png) | Slow response time due to large images |
| Split peas soup | ![screenshot](documentation/TESTING.md/lighthouse-mobile-split-peas.png) | ![screenshot](documentation/TESTING.md/lighthouse-desktop-split-peas.png) | Some minor warnings |
| Souerkraut soup | ![screenshot](documentation/TESTING.md/lighthouse-mobile-souerkraut.png) | ![screenshot](documentation/TESTING.md/lighthouse-desktop-souerkraut.png) | Some minor warnings |
| Sign up | ![screenshot](documentation/TESTING.md/lighthouse-mobile-signup.png) | ![screenshot](documentation/TESTING.md/lighthouse-desktop-signup.png) | Some minor warnings |
| Thank you | ![screenshot](documentation/TESTING.md/lighthouse-mobile-thankyou.png) | ![screenshot](documentation/TESTING.md/lighthouse-mobile-thankyou.png) | Some minor warnings |

## User Story Testing



| User Story | Screenshot |
| --- | --- | 
| As a new site user, I would like to sign up, so that I can get notifications when new recipes are uploaded. | ![screenshot](documentation/features/signing-up-feature.png) |
| As a new site user, I would like to read up on benefits about soups, so that I can get more encouraged to have healthier food choices. | ![screenshot](documentation/features/button-for-additional-information-feature.png) |
| As a new site user, I would like to see photos if finished meals, so that I can know how it should look like. | ![screenshot](documentation/features/image-feature.png) |
| As a returning site user, I would like to follow the site on social media, so that I can know of all the news of the site. | ![screenshot](documentation/features/footer-feature.png) |
| As a returning site user, I would like to watch the relevant videos, so that I can focus on cooking at the same time. | ![screenshot](documentation/features/button-for-video-tutorial-feature.png) |
| As a returning site user, I would like to see all recipes in one place, so that I can find them much easier next time. | ![screenshot](documentation/features/nav-bar-feature.png) |
| As a site administrator, I should be able to access sign up forms, so that I can thank the subcribing customers. | ![screenshot](documentation/features/thank-you-note-feature.png) |


## Bugs

There are no bugs that I am aware of.

## Unfixed Bugs

There are no bugs that I am aware of.
