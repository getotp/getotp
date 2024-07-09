# Free WhatsApp OTP API Service Documentation

Welcome to the Free WhatsApp OTP API service provided by GetOTP.co! This API allows businesses to send OTPs directly to customers via WhatsApp globally, without any hidden fees or subscriptions.

## Getting Started

To start using the Free WhatsApp OTP API, follow these steps:

1. **Sign Up**: Register your business on [GetOTP.co](https://getotp.co) to obtain your unique API key.

2. **Integration**: Implement our API in your preferred programming language. We provide support for various languages including PHP, Curl, ASP, Node.js, Python, Java, Ruby, C#, Perl, Kotlin, DIRT, Corona, and Swift.

3. **Send OTP**: Use the API endpoint to send OTPs to your customers' WhatsApp numbers.

## API Endpoint

The API endpoint for sending OTPs via WhatsApp is: https://getotp.co/api
## API Parameters

You can send OTPs using a GET request with the following parameters:

- `otp`: The OTP code to be sent.
- `to`: The recipient's WhatsApp number (including country code).
- `key`: Your unique API key obtained after signing up.

### Example Usage (Curl)


# Replace these variables with your actual values
OTP="123456"                      # The OTP to be sent
WHATSAPP_NUMBER="919876543210"    # Recipient's WhatsApp number (include country code)
API_KEY="your_api_key_here"       # Your unique API key from GetOTP.co

# Curl command to send OTP via WhatsApp
curl -X GET "https://getotp.co/api?otp=$OTP&to=$WHATSAPP_NUMBER&key=$API_KEY"

# Support and Contact

For any questions or assistance, please contact us at hi@getotp.co. Visit our documentation for more details about integrating and using the Free WhatsApp OTP API.

Privacy and Terms

	•	Privacy Policy: Read our Privacy Policy to understand how we handle your data.
	•	Terms & Conditions: Review our Terms & Conditions governing the use of our services.

About Us

GetOTP.co provides a free and secure platform for businesses to send OTPs via WhatsApp globally. We aim to simplify and streamline the OTP delivery process, ensuring reliability and ease of integration for our users.

Copyright © 2024 GetOTP.co. All rights reserved.
