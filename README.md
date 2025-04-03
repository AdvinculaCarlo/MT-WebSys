Scenario1: Show Off User Info with a Click!
Your team’s building a webpage to show off user details. There’s a “Load User Data” button and
an empty spot (a <div> with the ID userInfo). When someone clicks the button, you’ll pretend to
grab user info—like a name and bio—after a tiny wait (like a real internet fetch). Then, boom!
The userInfo spot updates with the name in a big heading (<h2>) and the bio in a paragraph
(<p>).
Write some JavaScript magic to:
1. Grab the button (give it a fun ID like loadBtn).
2. Find the userInfo <div>.
3. Make the button listen for a click.
4. When clicked:
○ Show “Loading data...” in the userInfo spot right away.
○ Wait 1.5 seconds (use setTimeout() to fake the delay).
○ After the wait, add an <h2> with a name (like “Alice Smith”) and a <p> with a bio
(like “Loves coding cool stuff!”).
○ Stick both the <h2> and <p> into the userInfo <div>.
Scenario 2: Build a To-Do List with Delete Power!
You’ve got a to-do list on a webpage where folks can add tasks (that part’s done). Now, it’s time
to add a “Delete” button next to each task (<li>). Click it, and poof—that task disappears! To
keep things smooth, you’ll use a trick called event delegation.
Write JavaScript to:
1. Find the <ul> holding the list (ID like todoList).
2. Add a click listener to the <ul>.
3. Check if the clicked thing is a “Delete” button (give it a class like delete-btn).
4. If it’s a “Delete” button, zap its parent <li> out of existence (use remove()).
Scenario 3: Switch Up Colors Like a Champ!
You’re adding a color switcher to a webpage. There’s a “Light Theme” button and a “Dark
Theme” button. Click “Light Theme” and the page goes bright (background light, text dark). Click
“Dark Theme” and it flips to cool and dark (background dark, text light).
Write JavaScript to:
1. Grab the “Light Theme” button (ID like lightBtn) and “Dark Theme” button (ID like
darkBtn).
2. Find the <body> with document.body.
3. Add a click listener to the “Light Theme” button.
4. When clicked, make the background light (like white) and text dark (like black).
5. Add a click listener to the “Dark Theme” button.
6. When clicked, make the background dark (like black) and text light (like white).
Scenario 4: Username Checker That Talks Back!
You’re making a signup form with a username box. As someone types, you’ll instantly tell them if
their username is good (at least 5 letters) or not. There’s a <p> below (ID usernameFeedback)
to show your message.
Write JavaScript to:
1. Find the username input (ID like usernameInput).
2. Grab the usernameFeedback <p>.
3. Listen for typing in the input (use the “input” event).
4. When they type:
○ Check how long the username is.
○ If it’s less than 5 letters, show “Username must be at least 5 characters!” in red.
○ If it’s 5 or more, show “Username is valid!” in green.
Scenario 5: Hide and Seek with a Button!
You’ve got a webpage with a secret section that’s hidden at first. There’s a “Show More” button
above it. Click it, and the section pops up, while the button switches to “Show Less”. Click
“Show Less”, and it hides again, flipping back to “Show More”.
Write JavaScript to:
1. Find the button (ID like toggleButton).
2. Grab the hidden section (ID like collapsibleContent, starts with display: none).
3. Add a click listener to the button.
4. When clicked:
○ If the section’s hidden (display: none), show it (display: block) and change the
button to “Show Less”.
○ If it’s showing (display: block), hide it (display: none) and switch back to “Show
More”.
