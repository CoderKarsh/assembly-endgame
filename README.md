# (Assembly: Endgame)[https://assembly-endgame-rosy-iota.vercel.app/]
Link: [https://assembly-endgame-rosy-iota.vercel.app/]

A simple hangman game but the programming languages of the world are at stake! Guess the correct word before you are only left with Assembly language.

## How to play
1. Click the letter that you think are in the word.
2. Guess the word before making 8 incorrect guesses.

### Learnings:
1. Learnt about clsx package for classNames
2. Challenged myself to only have 1 component and still make code readable
3. Many a11y features provided for development like aria-live, aria-label and made a few sr-only divs for better screen-reader responses.
4. Vercel deployment was failing as it was not able to install clsx package. Overriding the install command in "Build and Deployment" settings to "npm install && npm install clsx" worked
