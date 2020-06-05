# **Out of Context User Flows**

**Landing Page View**

Link: https://groverrichardson.github.io/out-of-context-wireframes/Landing%20Page/landing-page.html

_User clicks “New”_

-   Creates new session in database

-   Changes view to “Questions View” with option to enter new session name

_User clicks “Returning”_

-   Changes view to “Questions View” with option to enter in session name

_User clicks “How to Play”_

-   Changes view to “Instructions View”

</br>
</br>

**Instructions View**

Link: No link since view only contains text and one button.

_User clicks “Return to Main Menu” button_

-   Changes view to “Landing Page View”

</br>
</br>

**Questions View**

Link: https://groverrichardson.github.io/out-of-context-wireframes/Questions/questions.html

_User clicks “Submit” button_

If new user...

-   Adds session name given to database

-   Changes view to “Main View”

If returning user...

-   Searches for session with name given

-   Session found?

    -   Yes

        -   Changes view to “Main View” with session data

    -   No

        -   Returns error and clears input field

</br>
</br>

**Main View**

Link: https://groverrichardson.github.io/out-of-context-wireframes/Main%20View/main-view.html

_Universal Actions_

-   User presses “Edit” button

    -   All score fields are changed to input fields with current score as placeholder

    -   Edit button changes to save button

    -   Once save button is pressed current inputs are saved as new scores

_Judge Actions_

-   User clicks on favorite response

    -   Corresponding player’s score increases by 1

    -   Next card is drawn and displayed for everyone

    -   Corresponding player’s score is highlighted briefly to indicate score change

    -   Turn changes to next player in sequence

</br>
</br>

**Wildcard Next View**

Link: https://groverrichardson.github.io/out-of-context-wireframes/Wildcard%20Next/wildcard-next.html

_User presses “Next Card”_

-   New card is drawn and displayed for all users

-   Switches to wildcard view

-   New cards are drawn from deck with no wildcards until wildcard is claimed

</br>
</br>

**Wildcard Judge View**

Link: https://groverrichardson.github.io/out-of-context-wireframes/Wildcard%20Judge/wildcard-judge.html

_User presses “Claim” button_

-   Corresponding player’s points are increased 3 points

-   Wildcard is marked as used

-   View converted back to main view

</br>
</br>

**Answer Input View**

Link: https://groverrichardson.github.io/out-of-context-wireframes/Answer%20Input/answer-input.html

_User presses “Submit” button_

-   Response is saved to database

-   After all current player’s responses are entered, judge’s view is updated with responses
