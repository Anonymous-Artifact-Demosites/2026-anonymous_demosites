# The Tower of Babel: Systematically Analyzing Account Management Vulnerabilities in Web OAuth Integration

This is the demonstration website for our USENIX Security 2026 paper.

## Overview

Modern hybrid account systems, which integrate native account credentials with third-party identity providers (IdPs), introduce an unexplored attack surface within the account lifecycle. We define a vulnerability class, **identity state desynchronization**, which arises from inconsistent business logic during transitions such as identifier updates and IdP binding.

This demo site presents:
- **10 Vulnerability Primitives (Q1–Q10)**: Atomic logical omissions in hybrid account management
- **7 Attack Vectors (T1–T7)**: Composable exploit chains that enable account hijacking, persistent access, and account takeover
- **Real-world Case Studies**: Detailed demonstrations from major platforms including Pinterest, New York Times, 2Captcha, and Spotify

## Key Findings

- **39%** of evaluated websites (Tranco Top 500) are vulnerable to identity state desynchronization
- **10 websites** have acknowledged our responsible disclosure reports

## Demo Site Structure

- **Homepage** (`homepage.html`): Overview and navigation to case studies and workflow visualization
- **Case Studies** (`video.html`): Interactive demonstrations of attack vectors with video walkthroughs
- **Workflow Visualization** (`workflow.html`): Interactive exploration of the hybrid account management lifecycle and vulnerability primitives

## Browser Requirements

Please open the related URL with **Microsoft Edge** or **Google Chrome** for the best experience.

## Usage

Simply open `homepage.html` in a web browser to start exploring the demonstrations.

## License

This demonstration site is provided for research and educational purposes.
