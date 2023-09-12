# Backend Stage One Task

Welcome to Stage One of the Backend Internship task! This README file provides an overview of the task, its requirements, and instructions on how to set up and use the provided code.

## Objective

The objective of this task is to create and host an endpoint that accepts two GET request query parameters and returns specific information in JSON format. The required information includes:

- Slack name
- Current day of the week
- Current UTC time (within +/-2 minutes)
- Track
- GitHub URL of the file being run
- GitHub URL of the full source code
- Status Code (200 for success)

## Requirements

To meet the task requirements, the following steps have been implemented in the code:

- A Flask web application is used to create the endpoint.
- The endpoint accepts two GET query parameters: slack_name and track.
- The current day of the week is displayed.
- The current UTC time is returned with validation.
- The track is based on the track GET parameter.
- GitHub URLs for the specific file and full source code are included.
- A status code of 200 is returned.
- The response adheres to the specified JSON format.

## Getting Started

To set up and run the code locally for testing, follow these steps:

1. Install Flask if you haven't already:
   ```bash
   pip install Flask
