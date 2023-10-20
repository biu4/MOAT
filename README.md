**Fetching Data using Link:**
To access the data, use the following link:
[https://cdn.jsdelivr.net/gh/biu4/MOAT@main/index.html](https://cdn.jsdelivr.net/gh/biu4/MOAT@main/index.html)

**API Key for Azure AD Application:**
To authenticate your application with Azure Active Directory, you'll need the following API permissions:

1. **Directory.ReadWrite.All** - *Application* - Allows your application to read and write directory data.

2. **User.Read** - *Delegated* - Enables your application to sign in and access user profiles.

3. **Directory.ReadWrite.All** - *Delegated* - Grants permission to read and write directory data on behalf of the signed-in user.

Make sure to configure these permissions appropriately in your Azure AD application to ensure proper functionality.
