# GroceryRadar

GroceryRadar is a lightweight, community-driven grocery store recommendation system that leverages Instacart's infrastructure to help users discover the best nearby stores. Built with SwiftUI and Firebase, it provides a smart shopping experience by guiding users to Instacart-enabled stores and building community rankings through user feedback - no price storage, just intelligent store discovery.

---

## Current Status
**MVP Beta** - Core features implemented, premium subscription active, preparing for beta release

---

## Features

#### **Authentication & Security**
- **Email/Password Authentication**: Secure Firebase Auth integration
- **Email Verification**: Required verification with resend functionality
- **User Profile Management**: Display name, email, account settings
- **Comprehensive Error Handling**: User-friendly validation and error messages
- **Landing Page**: Modern onboarding with clear value proposition

#### **List Management System**
- **Multi-List Support**: Create, edit, delete, and archive unlimited lists
- **Smart Item Organization**: Categorize items (Produce, Dairy, Meat, Bakery, Pantry, Frozen, Other)
- **Quantity Management**: Intuitive quantity adjustment with swipe controls
- **Progress Tracking**: Visual progress indicators for each list
- **Real-time Synchronization**: Instant updates across devices via Firestore
- **Search & Filter**: Find items quickly with search functionality
- **Archive System**: Organize completed lists without losing data

#### **Community-Driven Store Discovery**
- **Nearby Store Discovery**: Find Instacart-enabled stores in your area
- **Direct Checkout Integration**: Seamless Instacart app/website integration
- **Community Rankings**: Personal and community store preferences
- **Feedback System**: Confirm which store you shopped at
- **Location-Based Results**: Find the best stores near your location

#### **Premium Subscription**
- **Stripe Integration**: Secure payment processing
- **Free Trial**: 7-day trial of premium features
- **Subscription Management**: Easy upgrade and cancellation
- **Premium Status Verification**: Reliable status tracking
- **Automatic Renewal**: Seamless subscription renewal

#### **Settings & Personalization**
- **Location Management**: Set and change location with adjustable search radius
- **Store Preferences**: Customize store selection and exclusions
- **Account Settings**: Profile management and data export
- **Premium Management**: View and manage subscription status
- **Haptic Feedback**: Customizable haptic responses

#### **User Experience**
- **Modern SwiftUI Interface**: Clean, intuitive design with smooth animations
- **Custom Tab Bar**: Easy navigation between main features
- **Responsive Design**: Optimized for all iOS devices
- **Accessibility**: VoiceOver support and accessibility features
- **Dark Mode Support**: Automatic theme switching

#### **Instacart API Integration**
- **Instacart Developer API**: Integration with Instacart's partner platform
- **Store Discovery**: Find and display nearby Instacart-enabled stores
- **Checkout Integration**: Direct links to Instacart store carts
- **Error Handling**: Robust API failure handling and fallback states

## **Architecture**

### **Frontend**
- **SwiftUI**: Modern declarative UI framework
- **MVVM Pattern**: Clean separation of concerns
- **Reactive Programming**: @Published properties and @EnvironmentObject
- **Custom Components**: Reusable UI elements and form fields

### **Backend**
- **Firebase Authentication**: Secure user management
- **Firestore Database**: Real-time data synchronization
- **Cloud Functions**: Server-side business logic and Stripe webhook handling
- **Firebase Cloud Messaging**: Push notifications

### **Data Sources**
- **Store Location Service**: Geographic store discovery
- **Instacart API**: Store discovery and checkout integration
- **Community Feedback**: User store selection and preference tracking
- **Rankings Database**: Personal and community store rankings

### **Payment Processing**
- **Stripe Integration**: Secure subscription management
- **Webhook Handling**: Automated subscription status updates
- **Premium Status Verification**: Reliable premium feature access

---

## **Technology Stack**

- **iOS**: SwiftUI, Swift 5.9+
- **Backend**: Firebase (Auth, Firestore, Functions)
- **Payments**: Stripe Integration
- **Location**: Core Location, MapKit
- **Testing**: XCTest, UI Testing
- **Version Control**: Git

---

**Built with ❤️ by Mik Driver** 

