# Incomplete Configuration Notification in the Street Protection App

**ID: US-BTC-528**

The Street Protection app notifies users about configurations that still need to be completed when they log in for the first time or after changes in the registration. This functionality ensures that all steps are finalized so that the app operates correctly and securely. If the app fails to send notifications to the server, it will retry up to three times, increasing the wait time between attempts. Once the configurations are completed, the notification disappears, ensuring that the user only sees information that is truly important.