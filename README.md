# project-2026
# Sukoon Community

**Compassionate. Connected. Accessible.**

Sukoon Community is a hackathon-built web platform designed to support **Muslim families raising children with special needs** by bringing together community, authentic Islamic guidance, and AI-powered assistance in one accessible space.

Our mission is to reduce isolation, remove barriers to finding support, and provide families with compassionate resources grounded in Islamic values.

---

## The Problem

Many Muslim families with children who have autism, ADHD, Down syndrome, sensory sensitivities, or other disabilities struggle to find:

- Supportive families with similar experiences
- Inclusive masjids and community groups
- Reliable Islamic guidance regarding accommodations and exemptions
- A safe place to ask sensitive questions without judgment

Existing social platforms are often overwhelming, not faith-centered, or lack accessibility features designed for neurodivergent users and caregivers.

---

## Our Solution

Sukoon Community creates a calming digital hub where families can:

- Connect with similar Muslim families
- Join inclusive community circles
- Learn authentic Islamic guidance about disability and caregiving
- Ask an AI Islamic companion personalized questions
- Navigate religious obligations with confidence and compassion

---

# Features

## Home Page

A simple, calming landing page introducing Sukoon Community.

Features include:

- Minimalistic design
- Explanation of the problem
- Overview of the platform
- Clear navigation into the application
- Soft colors and sensory-friendly layout

---

## Smart Family Matching

Families create a profile including:

- Child age range
- Support needs
- Languages spoken
- Preferred communication method
- Nearby mosque
- Interests
- Privacy preferences

The application then displays mock "Smart Matches" based on shared interests and support needs.

---

## Community Circles

Browse support groups such as:

- Autism & Salah
- First Ramadan with Autism
- Muslim Moms Support Circle
- Muslim Dads Support Circle
- Teen Autism
- Homeschooling
- Inclusive Masjid Families

Each circle includes:

- Member count
- Join button
- Interactive state
- Filtering

---

## Islamic Guidance & Fiqh FAQ

An accordion-based knowledge center covering topics including:

- Salah accommodations
- Sensory overload
- Religious exemptions
- Caregiving in Islam

Also includes a "Reminders of Hope" section featuring:

- Qur'an verses
- Hadith
- Encouraging reminders for caregivers

---

## Sukoon Islamic Scholar AI

An AI assistant built using the Gemini API.

Parents can ask questions like:

- "My autistic son struggles during Jumu'ah. What should we do?"
- "Is my child excused from fasting?"
- "How can I help my daughter during salah?"

### Features

- Functional chat interface
- Conversation history
- Proper markdown formatting
- Scholar-grounded responses
- Compassion-first system prompt
- Automatic fallback responses if no API key is provided

---

## Voice Accessibility

To improve accessibility:

- AI responses can be read aloud
- Text is cleaned before speech synthesis
- Arabic transliterations are spoken naturally
- Markdown formatting is removed before speech

Examples:

Instead of reading:

```
W A A L A I K U M
```

the application speaks:

> Wa Alaikum Assalam

This creates a far more natural listening experience.

---

## Sensory View

The application includes a dedicated sensory-friendly mode.

Instead of only changing colors, the layout also:

- Increases whitespace
- Reduces visual clutter
- Simplifies cards
- Enlarges buttons
- Improves spacing
- Increases text readability
- Creates clearer visual hierarchy

This allows users with mild visual impairments or sensory sensitivities to navigate the application more comfortably.

---

# Tech Stack

- React
- Tailwind CSS
- Lucide React
- React Hooks (`useState`, `useEffect`)
- Gemini 1.5 Flash API
- Web Speech API

---

# Design Principles

Sukoon Community was intentionally designed to feel:

- Calm
- Warm
- Compassionate
- Accessible
- Inclusive
- Easy to navigate

Design choices include:

- Rounded corners
- Gentle pastel palette
- High contrast text
- Large touch targets
- Responsive layouts
- Sensory-friendly spacing

---

# Responsive Design

The application is fully responsive and optimized for:

- Desktop
- Tablets
- Mobile devices

---

# Interactive Features

- Dynamic profile creation
- Smart family matching
- Join community circles
- Expandable FAQ accordions
- AI chat interface
- Voice playback
- Sensory mode toggle
- Smooth tab transitions

---

# Gemini API

The AI companion connects to:

```
https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent
```

If an API key is unavailable, the application gracefully falls back to pre-programmed scholar-informed responses, ensuring the demo remains fully functional.

---

# Accessibility

Accessibility was a primary focus throughout development.

Features include:

- Large readable typography
- High contrast text
- Screen-reader friendly structure
- Keyboard-friendly interactions
- Voice playback
- Sensory-friendly layout
- Reduced visual clutter
- Clear navigation hierarchy

---

# Inspiration

The word **"Sukoon" (سكون)** means:

> *Peace, tranquility, and comfort.*

Our goal is to provide exactly that for Muslim families navigating the unique challenges of raising children with special needs.

---

# Built For

Hackathon MVP

Designed to demonstrate how technology can foster:

- Community
- Compassion
- Inclusion
- Accessibility
- Faith-centered support

---

# Future Improvements

- Real authentication
- Secure family messaging
- Real-time family matching
- Location-aware mosque recommendations
- Scholar verification system
- Event scheduling
- Volunteer matching
- Therapist and specialist directory
- Parent resource library
- Multilingual AI support
- Progress tracking for community engagement

---

## Our Vision

No Muslim family should feel alone while raising a child with special needs.

Sukoon Community aims to build a future where every caregiver has access to compassionate support, authentic Islamic guidance, and a welcoming community—because every family deserves a place where they can find both **connection and peace**.
