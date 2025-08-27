1. Open your university's TR Fill-Up page in your browser.
2. Select any course from the course dropdown (this ensures the page loads all necessary fields).
3. Right-click anywhere on the page and choose Inspect (or press F12) to open Developer Tools.
4. By default, the Elements tab will be open. Click the Console tab to switch to the JavaScript console.
5. When you try to paste the code into the console, you might see this warning:
===============
Warning: Don’t paste code into the DevTools Console that you don’t understand or haven’t reviewed yourself. This could allow attackers to steal your identity or take control of your computer. Please type ‘allow pasting’ below and press Enter to allow pasting.
==============

6. Type exactly this in the console and press Enter: allow pasting
=============
If you get an error like Uncaught SyntaxError: Unexpected identifier 'pasting', just ignore it. The browser might sometimes behave this way but you can proceed to paste the code anyway.
=============
7. Now paste the provided JavaScript code (from this repo) into the console and press Enter.
8. The script will automatically select "Agree" from all dropdown menus on the page.

Thank you 
