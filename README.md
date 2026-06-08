# Agentic AI Curriculum & Calendar Orchestrator

## Overview

Agentic AI Curriculum & Calendar Orchestrator is an AI-powered automation system designed to generate personalized learning roadmaps and automatically schedule study plans with minimal user intervention.

The system combines Agentic AI, Google Docs, and Google Calendar to create a complete learning management workflow. Instead of simply generating a list of topics, the AI acts as an autonomous agent that plans a curriculum, organizes learning resources, creates structured documentation, and schedules study sessions on a user's calendar.

The project demonstrates the practical application of AI Agents in workflow automation by integrating Large Language Models (LLMs) with productivity tools to create an end-to-end educational planning solution.

# Problem Statement

Creating a structured learning roadmap often requires significant manual effort:
- Identifying relevant topics
- Organizing them in the correct sequence
- Finding learning resources
- Documenting the plan
- Scheduling study sessions

Most learners spend considerable time planning instead of learning.

This project automates the entire process using an AI Agent capable of making decisions, generating learning paths, and interacting with external productivity tools.

# Key Features

### Personalized Curriculum Generation
Users can specify:
- Learning topic
- Number of learning days
- Preferred start date

The AI dynamically creates a customized learning roadmap.

### Intelligent Topic Sequencing
Topics are arranged from:
- Beginner
- Intermediate
- Advanced

ensuring progressive learning.

### Automated Documentation
The system automatically:
- Creates a Google Document
- Generates structured content
- Adds daily learning objectives
- Includes descriptions and resources

### Automated Scheduling
The system:
- Calculates study dates
- Creates calendar events
- Maintains a fixed study schedule
- Eliminates manual calendar management

### End-to-End Automation
A single user request triggers the entire workflow.

# System Architecture

User Input → Chat Trigger → AI Agent → Gemini AI + Google Docs + Google Calendar → Final Response

# Components Used

## 1. Chat Trigger
Acts as the entry point of the workflow.
- Receives user requests
- Captures learning goals
- Sends requests to the AI Agent

## 2. AI Agent
Acts as the brain of the system.
- Understands user requirements
- Determines learning duration
- Calculates start dates
- Creates curriculum structure
- Calls Google Docs tools
- Calls Google Calendar tools
- Coordinates the entire workflow

## 3. Google Gemini Language Model
Provides reasoning and content generation capabilities.
- Generates curriculum content
- Creates daily learning topics
- Produces learning descriptions
- Suggests learning progression

## 4. Google Docs Integration
Creates a centralized learning document.
- Creates learning path documents
- Inserts curriculum content
- Stores learning objectives and resources

## 5. Google Calendar Integration
Automatically schedules learning sessions.
- Creates study events
- Sets reminders
- Maintains schedule consistency

# Technologies Used

- n8n Workflow Automation
- Agentic AI Architecture
- Google Gemini LLM
- Google Docs API
- Google Calendar API
- JSON Workflow Configuration


# Conclusion

Agentic AI Curriculum & Calendar Orchestrator demonstrates how modern AI agents can move beyond content generation and become autonomous workflow coordinators. By combining AI reasoning with document creation and calendar scheduling, the system transforms a simple learning goal into a complete, actionable learning plan.

