# Amazon-Polly-Test-Page

This is a test page for all the US and UK voices from Amazon Polly. It's a very slightly more advanced form of the default page in the official AWS Javascript SDK guide

- Follow steps 1 and 2 from this guide to make your own identity pool in Cognito: https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/getting-started-browser.html
- Replace YOURREGIONHERE and YOURIDENTITYPOOLHERE
- Open the HTML file and click away!

## Errors

The most common errors are 400s from Cognito because of a failed trust relationship/other IAM issue. Check developer tools and the response from Cognito to help diagnose the problem.
