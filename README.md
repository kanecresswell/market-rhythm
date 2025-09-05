🧠 Market Rhythm Toolkit

A modular, behaviorally-driven framework for analyzing intraday market structure using gap classification, session segmentation, and bid/ask imbalance dynamics. This toolkit is designed for traders and researchers seeking structural clarity, behavioral transparency, and empirical validation across trading sessions.

📦 Repository Contents

1. gap_session_flow.ipynb
Builds a 3-stage behavioral funnel:

Gap Type: Classifies sessions based on 07:00 and 09:30 opens relative to prior range.

Session Classification: Tags overlapping vs non-overlapping range structure.

Close Behavior: Identifies closes inside vs outside prior range.

Outputs:

Joint probabilities across all flows

Conditional bar charts and pie grids

Flow scoring and ratio analysis

2. bair_tpo_dashboard.ipynb
Generates a 7-panel dashboard for any session:

Traditional time-based TPO (prev PIT)

Volume and BAIR TPOs (pre-market, full session, PIT)

Candlestick chart with shaded POCs

Cumulative BAIR trace for PIT session

Supports:

Visual regime segmentation

Sentiment tracking via BAIR

Structural validation of reversal zones

3. daily_tpo_summary.py
Extracts daily reference levels:

Traditional TPO metrics (POC, VAH, VAL, High/Low)

Volume and BAIR POCs across session slices

Outputs a clean summary DataFrame for regime tagging or dashboard integration

🧠 Behavioral Philosophy
This toolkit is built on the belief that market structure tells a story — and that story can be segmented, scored, and validated. Each module is:

Modular: Designed for reuse and extension

Empirical: Grounded in observable session logic

Transparent: Outputs are interpretable and visually verifiable

🚀 Future Extensions
Rhythm engine with adaptive regime tagging

Interactive Dash dashboard for flow exploration

Behavioral scoring and clustering

Session memory and transition mapping

📚 Getting Started
Clone the repo and install dependencies (pandas, numpy, matplotlib)

Run gap_session_flow.ipynb to explore behavioral funnels

Use bair_tpo_dashboard.ipynb to visualize any session

Call summarize_daily_tpo_with_traditional() to extract reference levels
