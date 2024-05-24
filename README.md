# Stock & Market Analysis with GPT-4o and Llama Index: A Deep Dive into AI-Powered Insights

## Overview

This repository contains the code and data for analyzing the Dar es Salaam Stock Exchange (DSE) using advanced AI tools - GPT-4o and Llama Index. We demonstrate the use of these tools for extracting, processing, and analyzing financial data, providing insights into the stock market with high accuracy and efficiency.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Usage](#usage)
- [Methods](#methods)
  - [Method 1: LlamaParse with GPT-4o](#method-1-llamaparse-with-gpt-4o)
  - [Method 2: GPT-4o with SubQuestionQueryEngine](#method-2-gpt-4o-with-subquestionqueryengine)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contact](#contact)

## Introduction

In this repository, we explore how GPT-4o and Llama Index can be leveraged to analyze financial and stock market data from the Dar es Salaam Stock Exchange. The data is sourced from Solomon StockBrokers, a renowned stock market broker in Tanzania.

## Setup

To get started, clone the repository and install the required libraries:

```bash
git clone https://github.com/msamwelmollel/dse_analysis_gpt-4o.git
cd stock-market-analysis
pip install -r requirements.txt

Ensure you have the necessary API keys set up in your environment:
```bash
export OPENAI_API_KEY='your_openai_api_key'
export LLAMA_CLOUD_API_KEY='your_llama_cloud_api_key'

