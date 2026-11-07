# AI-Powered Hotel Food Ordering & Room Service Automation | n8n

An AI-powered hotel food ordering and room service automation system built with **n8n, JavaScript, Webhooks, and AI integrations**. The workflow automates the entire order lifecycle, from receiving guest requests to validating orders, routing them to the kitchen, and generating personalized customer confirmations.

## Features

- **Webhook-Based Order Processing:** Receives and processes food orders through HTTP endpoints.
- **Guest & Order Validation:** Validates guest information, order details, and required fields before processing.
- **Menu Availability Checks:** Verifies requested items and handles unavailable products.
- **Automated Price Calculation:** Calculates order totals based on menu items and quantities.
- **Intelligent Order Routing:** Directs orders to room service or restaurant pickup using multi-branch conditional logic.
- **Priority-Based Kitchen Queues:** Categorizes and routes orders based on priority and fulfillment requirements.
- **AI-Powered Validation:** Uses AI to detect inconsistencies, interpret order details, and improve validation.
- **Personalized Customer Communication:** Generates context-aware order confirmations and status messages using AI.
- **Error Handling:** Handles invalid requests, unavailable items, and processing failures with appropriate HTTP responses.

## Tech Stack

- **n8n:** Workflow orchestration and automation
- **JavaScript:** Custom business logic and data transformations
- **Webhooks & REST APIs:** Order intake and external integrations
- **AI / LLMs:** Intelligent validation and personalized message generation
- **JSON:** Structured order data and API responses

## Workflow Overview

<img width="1456" height="902" alt="Screenshot 2026-11-02 at 5 58 50 in the afternoon" src="https://github.com/user-attachments/assets/226881b7-66fb-4d54-ba37-32ea86960425" />
