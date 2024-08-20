# VisionGuard

**Empower Vision, Enhance Blind Businesses - Through AI Computer Vision**

- https://biz-vision.vercel.app/

## Overview

VisionGuard is an AI-powered assistant designed to empower visually impaired business owners by enhancing their ability to interact with customers, manage their business operations, and ensure safety. By utilizing advanced computer vision and AI technologies, VisionGuard provides real-time descriptions of customers, detects potential dangers, and assists with inventory and payment management.

## Inspiration

The inspiration for VisionGuard came from my close friendship with a partially blind individual who, despite their ambition, faced challenges due to their vision impairment. Their dream of starting a massage therapy business highlighted the difficulties that visually impaired individuals face in social interactions and business management. Additionally, statistics show that over 70% of working-age adults with significant vision loss are not employed full-time, and 27.7% live below the poverty line. VisionGuard aims to bridge this gap by providing the tools necessary for visually impaired entrepreneurs to succeed.

## Key Features

VisionGuard offers three main functionalities:

1. **Real-time Customer Detection**: Enhances social interactions by describing customers' facial expressions and appearances, helping business owners understand and respond to their customers' needs.
2. **Theft Detection & Safety Enhancements**: Detects potential dangers and environmental hazards, offering peace of mind and improving safety in the business environment.
3. **Inventory & Payment Management**: Streamlines business operations with easy-to-use inventory management and secure payment handling through Stripe.

## Tech Stack

- **Frontend**: 
  - React.js
  - Tailwind.css

- **Backend**: 
  - Flask
  - Python

- **APIs**: 
  - Google Gemini AI for computer vision
  - Twilio API for emergency contact alerts
  - Stripe API for payment processing

## Challenges

One of the major challenges faced during the development of VisionGuard was integrating the Stripe Payment system. As it was my first time implementing a payment system, understanding the intricacies of frontend and backend interactions was challenging but rewarding.

## Accomplishments

- Successfully integrated new and diverse technologies within a short time frame.
- Fine-tuned the Gemini AI language model for accurate and tailored content for visually impaired users.
- Completed the project solo, participating in a hackathon and overcoming numerous technical challenges.

## Lessons Learned

The development of VisionGuard has demonstrated the incredible potential of generative AI, particularly in assisting visually impaired individuals. It has also provided me with valuable experience in fine-tuning AI models and integrating complex systems like Stripe.

## Future Plans

The next steps for VisionGuard include implementing login authentication and a database for inventory management. The goal is to roll out the tool within the local community, making it accessible and impactful for blind business owners.

## How to Get Started

Clone the repository:

```bash
git clone https://github.com/yourusername/VisionGuard.git
cd VisionGuard
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```
