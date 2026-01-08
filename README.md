# prodev-mobile-setup

## Expo.dev Account Setup

This guide will walk you through creating a new account or logging in on Expo.dev.

### Creating a New Account

1. **Visit Expo.dev**
   - Go to [https://expo.dev](https://expo.dev)
   - Click on the **"Sign Up"** button in the top right corner

2. **Choose Your Sign-Up Method**
   
   You have three options to create an account:
   
   - **GitHub Account**: Click "Continue with GitHub" to sign up using your GitHub credentials
   - **Google Account**: Click "Continue with Google" to sign up using your Google account
   - **Email**: Enter your email address, username, and password to create a standalone account

3. **Complete Registration**
   - If using GitHub or Google, authorize Expo to access your account information
   - If using email, you may need to verify your email address by clicking the link sent to your inbox
   - Fill in any additional required information

4. **Welcome to Expo!**
   - Once registered, you'll be redirected to your Expo dashboard
   - You can now start creating and managing your mobile projects

### Logging In to an Existing Account

1. **Visit Expo.dev**
   - Go to [https://expo.dev](https://expo.dev)
   - Click on the **"Log In"** button in the top right corner

2. **Choose Your Login Method**
   
   Select the same method you used to create your account:
   
   - **GitHub**: Click "Continue with GitHub"
   - **Google**: Click "Continue with Google"
   - **Email**: Enter your username/email and password

3. **Access Your Dashboard**
   - After successful authentication, you'll be logged in to your Expo account
   - You can now access all your projects and account settings

### Login via Expo CLI

You can also authenticate with Expo from the command line:

```bash
# Install Expo CLI globally (if not already installed)
npm install -g expo-cli

# Login to your Expo account
expo login

# Follow the prompts to enter your credentials
```

Alternatively, use the newer EAS CLI:

```bash
# Install EAS CLI globally
npm install -g eas-cli

# Login to your Expo account
eas login

# Follow the prompts to enter your credentials
```

### Troubleshooting

- **Forgot Password**: Click the "Forgot password?" link on the login page to reset your password
- **Account Issues**: Visit [Expo's support page](https://expo.dev/support) for help
- **CLI Authentication**: If you encounter issues with CLI login, try `expo logout` or `eas logout` first, then login again

### Next Steps

After setting up your account, you can:
- Create a new Expo project
- Configure your development environment
- Deploy your mobile applications
- Access Expo's build and deployment services