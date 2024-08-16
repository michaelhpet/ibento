# ibento ('eventful'): Event Management System

## Overview

ibento is a comprehensive event management system that enables event creators to organize events and manage attendees. It offers features like QR code generation for event verification, social media shareability, notifications, and detailed analytics. This project is built using Nextjs.

## Table of Contents

- [Features](#features)
- [Running the Application](#running-the-application)
- [License](#license)

## Features

1. **Authentication and Authorization**

   - Secure authentication for event creators and attendees.
   - Authorization controls to ensure users only have access to their relevant data.

2. **QR Code Generation**

   - Automatic QR code generation for a registered guest.
   - QR codes can also be verified by event creator.

3. **Shareability**

   - Public events can be easily shared with a URL.

4. **Notifications**

   - Flexible notification system allowing both creators and attendees to set reminders for upcoming events.

5. **Analytics**
   - Detailed analytics dashboard for creators, providing insights into attendee numbers, ticket sales, and QR code scans.

## Running The Application

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
