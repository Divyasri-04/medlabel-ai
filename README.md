# 💊 MedLabel AI — Medicine-Label Information Assistant

### Scan. Understand. Stay Informed. 💊📸🤖

MedLabel AI is an AI-powered medicine-label information assistant that uses
Google Gemini's multimodal capabilities to analyze medicine labels from images.

Users can upload a photo of a medicine label and get information such as:

- 💊 Medicine name
- 📋 Strength
- 🧪 Active ingredients
- 🏭 Manufacturer
- 🔢 Batch number
- 📅 Manufacturing date
- ⏳ Expiry date
- ℹ️ Other information printed on the label

Users can also ask questions about the information extracted from the label.

## 🚀 Live Demo

[Open MedLabel AI](https://medlabel-ai-bxnrjenqvc9docirwjkntm.streamlit.app/)

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- Twilio WhatsApp API

## ✨ Features

- 📸 Medicine-label image analysis
- 🤖 AI-powered information extraction
- 💬 Conversational interaction
- 📲 WhatsApp summary
- 🌐 Streamlit deployment

## ⚙️ How It Works

1. Upload a medicine label image.
2. Gemini Vision analyzes the image.
3. MedLabel AI extracts the information printed on the label.
4. Ask questions about the extracted information.
5. Generate a summary and send it through WhatsApp.

## 🔐 Environment Variables

The application requires the following secrets:

```toml
GEMINI_API_KEY="your_gemini_api_key"
TWILIO_ACCOUNT_SID="your_twilio_account_sid"
TWILIO_AUTH_TOKEN="your_twilio_auth_token"
TWILIO_WHATSAPP_FROM="your_twilio_whatsapp_number"
TWILIO_CONTENT_SID="your_twilio_content_sid"
