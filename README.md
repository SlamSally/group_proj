# Template Repository for COMP SCI 2207/7207 Web & Database Computing (2023 Semester 1)

Contains environment files for WDC 2023. Copy this template for a general sandbox.

Auto commit/push/sync to Github is disabled by default in this template repository.
Enable the GitDoc extension to use this fucntionality (either in your VSCode settings, or in the Dev Container settings)

# Volunteer Organization Platform

## Overview

This project is a Volunteer Organization platform that allows users to sign up, log in, join volunteer organizations, view updates, RSVP for events, and more. The platform supports different user roles such as regular users, organization managers, and system admins.

## Features

- **User Features:**
  - Sign up and log in
  - Manage user information
  - Join a volunteer organization
  - View updates from organizations
  - See upcoming events and RSVP

- **Organization Manager Features:**
  - Manage user information
  - View members
  - Post updates publicly and privately
  - Create and update events
  - See RSVPs for events

- **System Admin Features:**
  - Manage user information
  - Manage users
  - Manage branches of the organization
  - Sign up other admins

- **Special Features:**
  - Email notifications using Nodemailer
  - Link to social media for updates and events
  - Progressive Web Application (PWA) with push notifications

## Technology Stack

- **Frontend:**
  - Vue.js
  - Vue Router
  - Vuex

- **Backend:**
  - Node.js
  - Express.js
  - MySQL

## Setup Instructions

### Prerequisites

- Node.js (>= 14.x)
- MySQL

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/UAdelaide/24S1_WDC_UG_Group112.git
   cd volunteer-organization-platform
