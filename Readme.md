# LoanQuick

Welcome to LoanQuick, a comprehensive loan management system designed to enhance financial inclusion for SMEs in India. This project was developed by Team Snipe for Hack Bangalore 2024. LoanQuick simplifies loan discovery and repayments, making financial services more accessible to small and medium enterprises.

## System Overview

LoanQuick consists of four main components, each serving a specific function within the ecosystem:

- **hb_flutter**: A mobile application developed in Flutter for end-users to interact with our services.
- **loanquick-backend**: The Node.js and Express.js based backend that handles all the API requests and business logic.
- **loanquick-dashboard**: A Next.js based frontend dashboard for lenders to manage loans, view analytics, and interact with borrowers.
- **Credit-Scoring**: A Flask server that hosts machine learning algorithms to predict loan eligibility, revenue and expenses, and loan requirements for companies.

## Repository Structure

This master repository contains submodules for each component of the LoanQuick system. Here's how the repository is organized:



Each submodule has its own README.md providing detailed information about setup, configuration, and usage.

## Getting Started

To get started with LoanQuick, clone this repository and its submodules using the following Git command:

```bash
git clone --recurse-submodules https://github.com/sirsho29/LoanQuick.git
