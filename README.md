# Repro for issue #6395

## Versions

firebase-tools: v12.5.4<br>
node: v18.16.1 <br>
refererence: https://github.com/firebase/quickstart-js/blob/master/auth/google-popup.html

# Steps

1. Run `firebase emulators:start --project demo-project`
2. Open "http://127.0.0.1:5000"
3. Click the "SIGN IN WITH GOOGLE" button
   - The popup should appear and you should be able to sign in as expected
4. Signed in user info should be visible on the web page
