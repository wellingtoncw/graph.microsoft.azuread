# graph.microsoft.azuread
Project to list all users in your Azure AD in a simple and functional way.

Instructions:
1. Navigate to Graph Explorer: Open your web browser and go to https://developer.microsoft.com/en-us/graph/graph-explorer.
2. Sign In: Click the Sign in button (usually on the left sidebar or top right) and log in using your Azure AD (Microsoft Entra ID) credentials.
3. Copy the Access Token: Locate the Access token tab positioned just below the main query input bar. Click it, then click the Copy button to copy the raw token string to your clipboard.
4. Implement in Your Application: Paste the copied token into your application's HTTP request configuration. You must pass it in the headers using the Authorization key with the Bearer scheme.
