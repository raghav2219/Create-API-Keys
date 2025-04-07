# Create-API-Keys
Instructions on API key creation and usage.

# Title: Step-by-step process of making API keys for Gemini and BigQuery:

## Gemini API Key Setup:
1. Go to the Google AI Studio: Open your browser and navigate to Google AI Studio.
2. Agree to Terms: If it's your first time, you'll likely need to agree to the terms of service.
3. Create a New API Key: Click on Create API key in a new project or Get API key if you already have a project set up.
4. Note Down Your API Key: A dialog box will appear with your new API key. Copy this key immediately and store it securely. This is the only time you'll see it.
5. Manage Your Keys (Optional): You can view and manage your API keys (and potentially regenerate them if needed) within Google AI Studio.

Security Note: Treat your Gemini API key like a password. Store it securely and do not share it publicly. If you lose it, you may need to regenerate it.

Usage Instructions: 

##BigQuery API Key Setup:
1. Head to the Google Cloud Console: Open your web browser and go to the Google Cloud Console. Make sure you're logged into the Google account associated with your project.
2. Select Your Project: If you have multiple projects, ensure the correct one is selected at the top.
3. Navigate to Credentials: In the left-hand navigation menu, go to APIs & Services and then click on Credentials.
4. Create Credentials: Click on the + Create credentials button at the top.
5. Choose API key: From the dropdown menu, select API key.
6. Your API Key is Created! Google Cloud will generate an API key for you.
7. Restrict Your Key (Highly Recommended): For security, you should restrict how this key can be used. Click on the Edit icon (pencil) next to the newly created key.
   * Application restrictions: Choose the type of application that will use this key (e.g., HTTP referrers for websites, IP addresses for       servers, Android apps, or iOS apps). Specify the allowed referrers, IP addresses, or app identifiers.
   * API restrictions: Select Restrict key and then choose the BigQuery API from the dropdown list. This ensures the key can only be used       for BigQuery operations.
8. Save Your Changes: Click Save at the bottom of the page.
9. Note Down Your API Key: Copy the API key and store it securely. You'll need this in your project's configuration.

Security Note: It is crucial to restrict the API key to only the BigQuery API and the specific application or IP addresses that will be using it. Avoid committing the API key directly to your codebase. Instead, use environment variables or a secure configuration management system.

Usage Instructions: 
