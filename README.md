# ZeroBounce1 MCP Server

Welcome to the ZeroBounce1 MCP Server README. This document provides an overview of the server capabilities and guides you through its features and functionalities.

## Overview

ZeroBounce1 is a powerful email validation server designed to enhance your email marketing ROI by ensuring that your email lists contain valid and deliverable addresses. Our server utilizes advanced email verification techniques to help businesses maintain clean email lists, reduce bounce rates, and improve overall email delivery metrics.

### Key Features

- **Email Validation**: Verify and validate email addresses to ensure that your email campaigns reach real and active users.
- **Reputation Protection**: Safeguard your sender reputation by decreasing bounce rates through effective email scrubbing.
- **High Accuracy**: Achieve up to 98% validation accuracy, ensuring that your email lists are as clean and deliverable as possible.

## API Tools and Methods

ZeroBounce1 offers several tools and methods to support your email validation needs:

### Email Validation Tools

1. **Validate Email v2**
   - **Function**: Validate
   - **Description**: Validates single email addresses to ensure they are active and deliverable.

2. **Validate Email v1**
   - **Function**: Validate Email with IP (v1)
   - **Description**: Validates email addresses and utilizes IP information for geolocation insights.
   - **Function**: Validate (v1)
   - **Description**: A basic email validation endpoint.

3. **Activity Data**
   - **Function**: Activity Data
   - **Description**: Gather insights into your subscribers' email engagement activities, including opens, clicks, forwards, and unsubscribes over various time frames.

### Detailed Usage

- **Validate Method**: This method returns a JSON response with detailed information about the email address, including its status (valid, invalid, catch-all, etc.), sub-status, account details, domain information, and more.
  
- **Activity Data Method**: This method provides engagement insights, helping you to better understand subscriber behavior and improve targeting and personalization of your email campaigns.

## Response Metrics

- **Response Time**: The server processes requests in 1 to 70 seconds, depending on the mail server's response time.
- **Supported Statuses**: The server reports statuses such as valid, invalid, catch-all, unknown, and more, along with sub-status details.
  
## Conclusion

ZeroBounce1 MCP Server is an essential tool for businesses looking to optimize their email marketing efforts by ensuring the validity and deliverability of their email lists. With its robust validation capabilities and comprehensive data insights, ZeroBounce1 helps you maximize the effectiveness of your email campaigns.

For more detailed information on how to integrate and use these tools, please refer to the detailed documentation provided with the server package.