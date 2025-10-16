# Mergington High School Activities

A web application that allows students to view extracurricular activities and teachers to manage student registrations at Mergington High School.

## Features

### For Students
- **View Activities** - Browse all available extracurricular activities with detailed information
- **Search** - Search activities by name or description
- **Filter Activities** - Filter activities by:
  - Category (Sports, Arts, Academic, Community, Technology)
  - Day of the week (Monday through Sunday)
  - Time of day (Before School, After School, Weekend)
- **View Details** - See activity descriptions, schedules, participant counts, and availability

### For Teachers
- **Authentication** - Secure login system for teachers
- **Register Students** - Sign up students for activities using their email
- **Unregister Students** - Remove students from activities
- **Manage Registrations** - View current participant lists for all activities

## Technology Stack

- **Backend**: FastAPI (Python web framework)
- **Database**: MongoDB (for storing activities and teacher accounts)
- **Frontend**: HTML, CSS, JavaScript
- **Server**: Uvicorn (ASGI server)

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
