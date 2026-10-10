# Football Turf Booking Platform: User and Administrator Roles

This document outlines the detailed user roles, permissions, and administrative structures for the football turf booking platform. A robust role-based access control (RBAC) system ensures security, smooth operations, and clear boundaries between players, team organizers, venue owners, and platform administrators.

## 1. User Roles Overview

The platform caters to four distinct user tiers:

- **Registered Player**: Standard users who book slots, join open games, and split payments.
- **Team Organizer**: Users who manage matches, invite friends, generate split-payment links, and handle roster coordination.
- **Turf Owner / Venue Manager**: Business operators who list venues, set pricing, manage time slots, and review booking logs.
- **Platform Administrator**: Super-users who oversee the entire ecosystem, handle dispute resolution, manage system configurations, and verify turf listings.

## 2. Detailed Role Breakdown & Permissions

### A. Registered Player
- **Profile Management**: Update personal details, preferred positions, skill level, and emergency contacts.
- **Booking & Payments**: Book available slots, pay individually, and view past or upcoming booking histories.
- **Match Discovery**: Browse open "Find a Player" listings to join casual community matches.
- **Reviews & Ratings**: Rate turfs and leave feedback based on past playing experiences.

### B. Team Organizer
- **All Player Permissions**: Retains all capabilities of a standard registered player.
- **Group & Match Creation**: Create private or public matches and set roster requirements.
- **Split-Payment Link Generation**: Split total booking fees across invited players and track payment statuses in real time.
- **Squad Management**: Invite players via links, handle roster replacements, and manage waitlists for dropouts.

### C. Turf Owner / Venue Manager
- **Venue Onboarding**: Register new turfs, upload high-resolution photos, specify precise dimensions, and list available amenities (e.g., parking, floodlights, shower rooms).
- **Inventory & Schedule Control**: Configure operational hours, block maintenance windows, and set custom pricing rules (peak vs. off-peak hours).
- **Booking Dashboard**: View real-time calendars, confirm manual offline bookings, and inspect payment settlement logs.
- **Add-On Management**: Manage inventory and pricing for equipment rentals (e.g., footballs, training bibs).

### D. Platform Administrator
- **User & Venue Verification**: Review and approve new turf registrations and business documents to prevent fraudulent listings.
- **Dispute & Refund Management**: Handle booking conflicts, process cancellations, and issue refunds according to platform policies.
- **System Monitoring**: Oversee platform analytics, monitor peak traffic trends, and track transaction volumes.
- **Content & Policy Moderation**: Moderate user reviews, ban abusive accounts, and update platform terms of service.

## 3. Role-Based Access Control (RBAC) Matrix

### Feature / Module Access

| Feature / Module | Player | Team Organizer | Turf Owner | Platform Admin |
|---|---|---|---|---|
| Browse & Book Turfs | Yes | Yes | No | Yes (View Only) |
| Split Payments & Invite Friends | No | Yes | No | No |
| Create & Manage Turf Venues | No | No | Yes | Yes (Full Control) |
| Set Pricing & Time Slots | No | No | Yes | Yes (Override) |
| Resolve Booking Disputes | No | No | No | Yes |
| Verify New Vendors | No | No | No | Yes |
| View Booking History | Yes | Yes | Yes | Yes |
| Manage User Accounts | No | No | No | Yes |
| Generate Reports & Analytics | No | No | Yes (Own Venue) | Yes (All) |

---

**Version**: 1.0  
**Last Updated**: October 2026
