# Around - Event-Based Social App Prototype

This is a high-fidelity iPhone 15 Pro prototype for an event-based social app with a map-centric UI similar to Waze.

## Overview

Around is a social networking app that helps users discover and join events happening around them. It features a map-centric interface that displays nearby events and allows users to tap to view details and join events.

## Pages & Navigation Flow

The prototype consists of the following pages:

1. **index.html** - Landing/Login page with sign-in form
   * Links to home.html upon signing in

2. **home.html** - Main app page with map and event discovery
   * Features a map with event markers
   * Shows nearby events in horizontal scrolling cards
   * Navigation to other sections via bottom tab bar

3. **events.html** - Full list of events organized by date
   * Shows today's events, tomorrow's events, and weekend events
   * Filterable by categories and time periods

4. **event-details.html** - Detailed view of a specific event
   * Shows event information, location, description, attendees
   * Option to get tickets or join the event

5. **profile.html** - User profile page
   * Shows user information and stats
   * Lists events the user is attending
   * Navigation to settings

6. **settings.html** - App settings and preferences
   * Account settings
   * App preferences
   * About section and sign out option

## Features

- **Map-centric UI**: Discover events on an interactive map
- **Event Discovery**: Browse events by proximity, date, or category
- **Social Elements**: See who's attending events
- **User Profiles**: Track your events and connect with others
- **Settings Management**: Control app preferences and account settings

## Design Notes

- Designed for iPhone 15 Pro dimensions (393x852 pixels)
- Uses Apple's design language and UI patterns
- Features a custom bottom tab bar navigation
- Follows iOS status bar and safe area guidelines

## How to Use

1. Start with `index.html` for the login experience
2. Navigate through the app using the links and bottom tab bar
3. Explore the map on the home page to discover events
4. Check out event details and user profiles
5. Test the settings page for preference management

## Technology

- HTML5
- Tailwind CSS
- Font Awesome icons
- Optimized for modern mobile browsers

## Future Enhancements

In a real application, these pages would be connected to a backend with:
- User authentication
- Real-time map integration
- Event creation and management
- Social networking features
- Push notifications