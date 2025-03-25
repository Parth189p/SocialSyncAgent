# Social Media Agent(Autobuzz AI) 🤖

An intelligent agent that automates content curation and social media posting by processing various online sources and generating platform-specific content.This project is a Social Media Content Automation Agent that streamlines content creation and publishing across multiple platforms. The agent takes input links from various sources such as blogs, tweets, GitHub repositories, and more, scrapes relevant data, generates content reports, and creates platform-specific posts for social media.

![Project Status: Active](https://img.shields.io/badge/Project%20Status-Active-green)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![LangGraph](https://img.shields.io/badge/LangGraph-Enabled-orange)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)

## 📁 Repository Details

This repository contains only the README to showcase the project's functionality and potential.

The source code is not publicly available but can be demonstrated upon request.

## 🌟 Features

- **Multi-Source Content Aggregation**
  - Scrapes content from diverse sources:
    - Blog posts
    - Tweets/X posts
    - GitHub repositories
    - Other online content
  - **New:** Parallel processing of multiple links
  - **New:** Intelligent content aggregation from related sources

- **Smart Content Processing**
  - Analyzes and synthesizes information from multiple sources
  - Generates comprehensive content reports
  - Creates platform-optimized posts automatically
  - **New:** Automated image extraction and processing
    - Screenshots of linked content
    - Image extraction from source documents
    - AI-powered image ranking for relevance
    - Custom image upload support

- **Platform-Specific Optimization**
  - Automatically adapts content for different platforms:
    - Twitter/X (character limit compliant)
    - LinkedIn (professional formatting)
  - Maintains platform-specific tone and style

- **Human-in-the-Loop Feedback**
  - Interactive feedback system
  - Post revision capabilities
  - Content adjustment options
  - Approval workflow
  - **New:** Image selection and customization
    - Choose from extracted images
    - Upload custom images
    - Modify image rankings

- **Automated Scheduling**
  - Smart scheduling system
  - Customizable posting dates
  - Priority management
  - Schedule modification during feedback

- **Direct Social Media Integration**
  - Automated posting to connected accounts
  - Multi-platform support
  - Authentication handling

## 🔄 Workflow Overview

<div align="center">
  <img src="./Architecture_1.png" alt="Social Media Agent Architecture" width="85%">
</div>

<details>
<summary><b>📊 Detailed Workflow Diagrams</b></summary>

<div align="center">
  <h4>Input & Processing Flow</h4>
  <img src="./part-1.png" alt="Input & Processing Flow" width="80%">
  
  <h4>Output & Distribution Flow</h4>
  <img src="./part-2.png" alt="Output & Distribution Flow" width="80%">
</div>
</details>

---

### Process Steps:

1. **Input Processing**
   - User provides content source links
   - System initiates content scraping

2. **Content Analysis**
   - Data extraction from sources
   - Content synthesis and report generation

3. **Post Generation**
   - Platform-specific content creation
   - Character limit optimization
   - Tone and format adaptation

4. **Human Feedback Loop**
   - Content review
   - Revision requests
   - Schedule adjustments
   - Priority modifications
   - Final approval

5. **Automated Posting**
   - Schedule execution
   - Multi-platform distribution
   - Status monitoring

## 🏗️ Demo

The system utilizes LangGraph Studio for workflow orchestration and AgentBox for the user interface, creating a seamless and efficient content management pipeline.

![Adentbox UI](./Autobuzz_01.gif)

## 🔮 Future Enhancements

- Additional platform support
  - Reddit integration
  - YouTube video content processing
  - Extended social media platform coverage

- Natural Language Input Processing
  - Topic-based content generation
  - Automatic relevant source discovery
  - Custom source link addition
  - Multi-source content aggregation

- Slack Integration
  - Direct message-based post creation
  - Automated cron job scheduling
  - Link processing through Slack
  - Real-time notifications

- Enhanced Content Generation
  - Automated blog post creation
  - Multi-format content adaptation
  - SEO optimization
  - Rich media support

- Advanced Priority Management
  - Multi-level priority system
  - Topic-based prioritization
  - Time-sensitive content handling
  - Platform-specific priority queues

- Advanced scheduling algorithms
- Enhanced content analysis
- Improved personalization
- Analytics integration

## 📝 Note

This project demonstrates the capability to automate and streamline social media content management while maintaining content quality through human oversight.
