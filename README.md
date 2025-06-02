 # MEV Bot Detector Dashboard

A Streamlit-powered dashboard that scans Ethereum blocks to detect and explain suspicious on-chain activity. This tool helps users identify patterns commonly associated with bots, including:

: High Gas Transactions  
: Sandwich Attacks  
: Anomalous Transactions  
: MEV Bot Clusters

This project is useful for traders, developers, and analysts who want a clearer view of hidden activity on the Ethereum network.

---

## Features

: Beginner-friendly explanations for each suspicious behavior  
: Real-time data fetched from the Ethereum blockchain  
: Custom thresholds for high gas price detection  
: Live counters for high gas transactions, sandwich attacks, and anomalies  
: Secure API integration using Streamlit secrets  
: Performance optimized to fetch and analyze up to 100 blocks per scan within 60 seconds

---

## How It Works

The dashboard fetches a set number of recent Ethereum blocks using the Etherscan API. It analyzes transactions to:

: Detect high gas usage based on a defined threshold  
: Identify sandwich attacks by comparing gas prices and execution order  
: Flag transactions with low transfer value but unusually high gas costs  
: Group similar suspicious transactions into MEV bot clusters

---

## Technologies Used

: Python  
: Streamlit  
: Pandas  
: Requests  
: Etherscan API

---

# This code was built by Dairus
