# LS Lines — NBA Analytics & Research Application

LS Lines is an AI-assisted NBA analytics and research application designed to bring together historical performance data, current player information, matchup context, and saved research workflows in one interface.

This public repository presents the project from a product, analytics, and business-analysis perspective. The production application is maintained separately.

## Project Purpose

The goal of LS Lines is to make NBA research easier to explore, compare, save, and evaluate.

The application brings together multiple data sources and presents them through structured workflows that help users understand:
- historical player and team performance
- recent form and playing-time context
- current availability information
- matchup comparisons
- analytical projections
- saved research and historical outcomes
- data freshness and coverage limitations

## My Role

I developed LS Lines as an AI-assisted personal project.

My primary contributions include:
- defining functional and analytical requirements
- prioritizing product improvements
- testing user workflows and application behavior
- reviewing analytical outputs
- investigating missing, stale, or inconsistent data
- improving navigation and data transparency
- monitoring deployment and data-refresh reliability
- managing iterative application updates with AI assistance

I do not claim independent authorship of every component or professional software-engineering experience.

## Business Analysis Examples

### 1. Research Tracking Workflow

I identified that users needed to distinguish between information they were simply viewing and research they intentionally wanted to save and evaluate later.

I defined a review-and-confirm workflow so that saved research represents an intentional user action and contains the information required for later outcome tracking.

### 2. Data Transparency

An empty result could be caused by several different conditions, including:
- missing source data
- stale information
- collection limits
- restrictive filters

I prioritized clearer system messages and fallback exploration so users can better understand why information is unavailable.

### 3. Analytical Requirements

Historical averages can become misleading when a player's current role or playing time has changed.

I refined requirements to incorporate:
- current-season evidence
- recent playing-time context
- historical comparison windows
- reported availability information

These features provide additional context but should not be interpreted as validated causal predictions.

### 4. User Experience

Through hands-on testing, screenshots, and comparison with other analytics products, I identified areas where navigation and information density could be improved.

I prioritized:
- clearer visual hierarchy
- integrated player and game research
- easier return navigation
- more transparent data-coverage indicators

## Technical Exposure

The project has given me hands-on exposure to:

- Python
- SQL
- Streamlit
- pandas
- NumPy
- SQLite
- REST APIs
- Git / GitHub
- Docker
- Render deployment
- scikit-learn

## Data & Reliability

The application includes workflows for:
- data reconciliation
- duplicate checks
- player and team matching
- missing-data handling
- local caching
- data freshness indicators
- request and collection controls
- saved research records
- outcome tracking
- deployment monitoring

## Project Status

LS Lines is an analytical prototype under active development.

It should not be interpreted as:
- a validated predictive system
- a production-grade commercial service
- evidence of advanced proficiency in every technology used

The project is primarily intended to demonstrate my experience with business requirements, analytics, data validation, product iteration, and technology-enabled problem solving.

## Screenshots

Screenshots of selected analytics, exploration, and workflow features will be added here.
