# Access Control System for Rental Point Information System

## Description
Implementation of a hybrid access control model for rental point automation system combining RBAC, MAC, and ACL.

## Features
- Role-Based Access Control (Admin, Manager, Client)
- Mandatory Access Control (PUBLIC, INTERNAL, CONFIDENTIAL)
- Access Control Lists with owner-based privileges
- Access logging and statistics visualization

## Quick Start in Google Colab

1. Open [Google Colab](https://colab.research.google.com/)
2. Create new notebook
3. Copy and paste `access_control_system.py` code
4. Run cell (Shift+Enter)

## Local Installation

```bash
git clone https://github.com/YOUR_USERNAME/rental-access-control.git
cd rental-access-control
pip install -r requirements.txt
python access_control_system.py
