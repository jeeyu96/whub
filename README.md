# WHub - Proof of Concept (POC)

## Overview

**WHub** is a mobile platform designed for open-minded couples and singles to connect, share exclusive content, and arrange physical meetups. This project aims to provide a safe, exclusive environment for couples in open relationships to engage in content sharing, social interactions, and private meetups. The Proof of Concept (POC) for this project is built using React Native to target both Android and iOS platforms.

WHub's primary objective is to create an ecosystem where verified couples can share personal content and find like-minded individuals for real-world and online interactions in a secure and private environment.


### Features

- **Content Sharing**: Users can upload and share exclusive content (photos, videos) with other verified users. This content is only available for paying subscribers.
- **Verified Users**: Couples and singles can apply for verification, ensuring authenticity and security within the community.
- **Premium Subscription**: Premium members gain access to additional features, such as exclusive content from verified couples and special matching services.
- **Matchmaking**: Similar to popular dating apps, WHub allows users to "swipe" on profiles of other users to indicate interest. Matches can lead to conversations and, eventually, in-person meetups.
- **Real-World Meetups**: Verified couples and singles can arrange private gatherings at designated, exclusive locations (called WHotels) with all necessary amenities and discretion.
- **Events & Experiences**: Users can participate in events organized within the WHotel, such as social gatherings, private encounters, and themed experiences.
- **Merchandise Shop**: An integrated online store allows users to purchase exclusive items like clothing, accessories, and other products. Users can even purchase products used during live events or streams.
- **Live Streaming & PPV**: The platform allows live streaming where couples can share moments with their followers. Users can purchase exclusive, live-viewed items during the stream.
- **Data Privacy & Security**: Privacy is of utmost importance, and user data is handled with advanced encryption techniques to ensure confidentiality and protection from unauthorized access.


## Technology Stack

- **React Native**: Cross-platform development for iOS and Android mobile applications.
- **Redux**: State management for handling global states across the application.
- **Firebase**: Authentication, real-time database, and cloud storage to handle user verification, content storage, and secure communication.
- **Node.js**: Backend services for matchmaking algorithms, subscription management, and live-event streaming coordination.
- **Stripe API**: Integration for payment processing, including subscription services and in-app purchases.
- **Amazon S3**: Secure cloud storage for user-generated content and media.

## Future Roadmap

This Proof of Concept focuses on the following key features for the MVP (Minimum Viable Product):
1. **User Authentication**: Sign-up/login functionality using Firebase Authentication.
2. **Content Sharing**: Basic implementation of photo and video uploads for verified users.
3. **Matchmaking Algorithm**: Implementing a swipe-based matching system for couples and singles.
4. **In-App Purchases**: Integrating Stripe for premium subscription models.
5. **Private Meetups**: Early-stage implementation of creating events for private meetups.

### Planned Features for Full Release
- **Advanced Matchmaking**: An enhanced algorithm to optimize matching based on preferences, activity, and history.
- **WHub Hotels (WHotels)**: Integration of location-based services to find and book exclusive meetup venues.
- **Event Streaming and Merchandise Purchase**: Allow users to buy items used in live events or streaming sessions in real-time.
- **Multi-Language Support**: Expand to a global audience with localization.

## Getting Started

To get started with the WHub POC, follow the instructions below.

### Prerequisites

- **Node.js** (>= 14.x)
- **React Native CLI**
- **Android Studio** (for Android Development)
- **Xcode** (for iOS Development)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jeeyu96/whub.git
   cd whub

