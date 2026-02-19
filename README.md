# Lex Translate Bot

## How it works
1. User selects target language
2. User inputs text
3. Bot returns translated text

## Technologies used 
- Amazon Lex (chatbot)
- AWS Lambda (fulfillment)
- Amazon Translate (translation service)

## Setup
- Create Lex bot with slots: `language`, `text`
- Create Lambda function with `translate:TranslateText` permission
- Connect Lambda as fulfillment to Lex intent
- IMPORTANT- Make sure Amazon Translate is enabled in your AWS region.

## Example
Input:
- Language: german
- Text: welcome

Output:
- Willkommen




