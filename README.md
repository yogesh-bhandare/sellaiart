# SellAiArt: Enabling AI Artists to Create and Profit

### Overview

SellAiArt is a web platform designed to empower AI artists by providing tools to generate, showcase, and sell their AI-generated artwork. It bridges the gap between artistic creativity and commerce, offering a seamless experience for artists to monetize their work. This repository represents the core platform, with image generation capabilities extended via the [SellAiArt Microservice](https://github.com/yogesh-bhandare/sellaiart-microservice).

### Motivation

Inspired by Botto, a decentralized AI artist that combines algorithmic art generation with human judgment, SellAiArt was conceived to simplify and democratize AI art creation. The platform focuses on convenience and scalability, allowing artists to focus on creativity while the platform handles storage, presentation, and transactions.

![Demo](src/static/assets/demo.gif) 

### Features
   - **AI Art Generation:** Create unique AI artworks using advanced models from Replicate.ai with tailored prompts for high-quality outputs. (See [SellAiArt Microservice](https://github.com/yourusername/sellaiart-microservice) for dedicated image generation.)
   - **Secure Storage:** AWS S3 ensures safe and reliable storage of all generated art assets.
   - **Monetization Tools:** Integrated Stripe payments for seamless and secure transactions.
   - **Exclusive Content:** Protects assets from unauthorized downloads until purchase.

### Tech Stack

   - **Django Backend:** Facilitates core functionalities with Jinja templates for fast prototyping and Tailwind CSS for sleek, responsive design.
   - **Replicate.ai Integration:** Streamlines AI art creation by leveraging advanced pre-trained models.
   - **Storage & Security:** AWS S3 integration ensures secure file uploads and storage.
   - **Payment Gateway:** Stripe API integration for secure and effortless payment processing.
   - **Deployment:** CI/CD with Docker and GitHub Actions ensures a robust and scalable platform.
   - **Microservice:** Image generation handled by [SellAiArt Microservice](https://github.com/yourusername/sellaiart-microservice).

## Getting Started

To get started with SellAiArt, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sellaiart.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd sellaiart
   ```
   
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
4. Start the development server:
   ```bash
   python manage.py runserver
   ```
   
5. Open your browser and visit `http://localhost:3000` to use SellAiArt.
