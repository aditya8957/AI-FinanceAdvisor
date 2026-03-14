AI Financial Advisor is a full-stack intelligent financial planning system that provides personalized financial insights using generative AI.

The application helps users analyze their financial health by evaluating income, expenses, savings, and financial goals. Using AI-powered reasoning and financial analytics, the system generates recommendations for budgeting, saving, and investment planning.

The platform combines a React-based frontend interface, a Node.js backend, and Google Gemini AI to deliver interactive financial insights and goal-based planning strategies.

Key Features
Personal Financial Analysis

Users can input financial information such as:

Monthly income

Expenses

Savings

Debts

The system evaluates financial indicators including:

Budget allocation

Savings ratio

Debt-to-income balance

Goal-Based Financial Planning

Users can define financial goals such as:

Emergency fund

Home purchase

Education savings

Travel planning

The system calculates required monthly contributions and suggests strategies to achieve these goals.

AI-Powered Financial Advice

The system integrates Google Gemini AI to generate contextual financial insights such as:

Budget optimization

Expense reduction suggestions

Investment diversification

Debt management strategies

Financial Analytics

The analytics module processes financial inputs to generate meaningful metrics that help users understand their financial behavior.

OCR-based Data Extraction

The system includes an OCR module that can extract financial information from uploaded documents or receipts to assist in automated financial tracking.

System Architecture:

Frontend (React + Vite)
        │
        ▼
Backend API (Node.js)
        │
        ├── Analytics Service
        ├── Category Service
        ├── OCR Service
        └── Gemini AI Service
        │
        ▼
Google Gemini AI API
