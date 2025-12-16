📘 Oracle HCM Cloud – Talent Management Project
===============================================

This document provides a complete overview of the **Talent Management** configurations executed in Oracle HCM Cloud, covering:

*   **Talent Profile / Profile Management**
    
*   **Goal Management**
    
*   **Performance Management**
    

These configurations support workforce development, appraisals, career planning, skill tracking, goals, and performance cycles.

🧩 1. Talent Profile (Profile Management)
=========================================

Talent Profiles track employee skills, qualifications, competencies, education, languages, certifications, achievements, and rating history.

🔧 **Configurations Performed**
-------------------------------

### **1\. Manage Lookups**

Created lookup values used across Talent Profiles such as:

*   Good | Very Good | Outstanding
    
*   Above Average | Moderate | Excellent
    

### **2\. Manage Descriptive Flexfields (DFFs)**

Added custom fields to capture additional profile information:

*   Custom rating categories
    
*   Employee potential indicators
    
*   Notification preferences
    

Example custom values:

*   Raghav, Kumar identifiers
    
*   Potential metrics: Key Talent, Rising Talent, Top Talent
    

### **3\. Manage Workforce Profile Value Sets**

Examples created:

*   Performance Level
    
*   Potential Level
    
*   Behavior Rating
    

### **4\. Manage Profile Rating Models**

Created models for:

*   Performance Ratings
    
*   Potential Ratings
    
*   Proficiency Ratings
    
*   Competency Ratings
    

Examples:

*   Outstanding → 5 Star
    
*   Very Good → 4 Star
    
*   Good → 3 Star
    
*   Average → 2 Star
    
*   Poor → 1 Star
    

### **5\. Manage Profile Content Types**

Configured content types:

*   Competencies
    
*   Certifications
    
*   Languages
    
*   Experience
    
*   Education
    
*   Awards
    
*   Licenses
    

### **6\. Manage Profile Content Items**

Examples created:**Competencies**: Analytical Thinking, Communication, Interpersonal Skills**Education**: MBA, BTech, BA, BSc, BBA**Languages**: English, Hindi, Telugu, Tamil**Certifications**: Core HR Certification, Sales Certifications

### **7\. Manage Model Profiles**

Created job/position-specific competency and qualification models such as:**Sales Manager Model Profile:**

*   Skills: Communication, Analytical Thinking
    
*   Education: MBA Marketing
    
*   Experience: 4 Years Sales Experience
    
*   Certifications: 2 Sales Certifications
    
*   Languages: English, Hindi
    

🎯 2. Goal Management
=====================

Goal Management enables organizations to assign, monitor, and evaluate goals for employees.

🔧 **Configurations Performed**
-------------------------------

### **1\. Descriptive Flexfields**

Added DFFs for:

*   Goal tracking attributes
    
*   Goal success measures
    
*   Custom date ranges (Jan–Dec 2022)
    

### **2\. Manage Lookups**

Created lookup values used inside goals such as:

*   Star ratings
    
*   Weightages (50%, 10%, 20%)
    
*   Achievement labels: Very Good, Average, Good
    

### **3\. Profile Options**

Enabled goal sharing, approvals, visibility, and scheduled processing.

### **4\. Eligibility Profiles**

Used to identify employees who qualify for:

*   Goal Plans
    
*   Goal Plan Sets
    
*   Performance cycles
    

### **5\. Manage Goal Library**

Created **standard/global goals**, such as:

*   Generate 70% Sales Revenue
    
*   Create Brand Awareness
    
*   Build a Sales Team of 10 Members
    
*   Introduce 3 New Products
    
*   Achieve 40% Conversion via Advertising
    
*   Conduct 20 Sales Programs
    

### **6\. Goal Plans**

Created Goal Plans for evaluation period **Jan–Dec 2025**, including weightages:

GoalRatingIndividual WeightFinal WeightGenerate 70% RevenueVery Good40%50%Create Brand AwarenessAverage10%10%Conduct 20 Sales ProgramsExtremely Good10%5%Build Sales TeamGood10%10%Introduce 3 New ProductsVery Good10%20%Achieve 40% ConversionPoor20%–

### **7\. Goal Plan Sets**

Grouped Goal Plans for mass assignment.

### **8\. Document Types**

Defined document types for goal tracking and review.

### 🧭 **End-to-End Goal Management Flow**

**Step 1:** Create goals in Goal Library**Step 2:** Define Review Period (Jan 2025–Dec 2025)**Step 3:** Create Performance Document Type**Step 4:** Create Eligibility Profile**Step 5:** Create Goal Plan**Step 6:** Run Goal Scheduled Process (Mass Assign Goals)

📘 3. Performance Management
============================

Performance Management evaluates employees through self-assessments, manager reviews, scoring, feedback, and documentation.

🔧 **Configurations Performed**
-------------------------------

### **1\. Descriptive Flexfields**

Added custom fields inside:

*   Performance Document
    
*   Review sections
    
*   Feedback section
    

### **2\. Profile Options**

Enabled:

*   Document routing
    
*   Self-evaluation
    
*   Multi-rater feedback
    
*   HR document visibility
    

### **3\. Performance Roles**

Assigned roles such as:

*   Human Resource Manager
    
*   HR Specialist
    
*   Application Implementation Consultant
    
*   Project Manager
    

### **4\. Manage Performance Process Flows**

Created custom process flows with the following stages:

*   **Goal Setting**
    
*   **Worker Self Evaluation**
    
*   **Manager Evaluation**
    
*   **Review Meetings**
    
*   **Final Feedback Exchange**
    
*   **Setting Goals for Next Year**
    

### **5\. Eligibility Profiles**

Used to assign performance documents based on:

*   Department
    
*   Grade
    
*   Legal Entity
    
*   Job Function
    

Example: “Get at least 2 certifications” group.

### **6\. Create Performance Template Sections**

Sections included:

*   Goals
    
*   Profile Content
    
*   Overall Summary
    
*   Questionnaire
    
*   Worker Final Feedback
    
*   Manager Final Feedback
    

### **7\. Manage Performance Templates**

Created templates for:

*   Annual Performance Document
    
*   Manager Evaluation Document
    
*   Self-Assessment Document
    

### **8\. Review Period**

Example:

*   Jan–Dec 2022
    
*   Jan–Dec 2025
    

### **9\. Performance Document Type**

Examples created:

*   2022 Annual Review
    
*   2021 Annual Review
    
*   2025 Annual Performance Document
    

### **10\. Eligibility Batch Process**

Used to mass-assign performance documents to 5000+ employees.

🧭 **End-to-End Performance Management Flow**
---------------------------------------------

1.  **Create Goals** → Goal Library
    
2.  **Assign Goals** → Goal Plan
    
3.  **Run Eligibility** → Assign Performance Docs
    
4.  **Worker Self Evaluation**
    
5.  **Manager Evaluation**
    
6.  **Review Meeting**
    
7.  **Feedback Sharing**
    
8.  **Document Completion**
    
9.  **Set Goals for Next Year**
    

🧩 Full Talent Management Architecture (Summary)
================================================

ModuleKey Configurations**Talent Profile** : Content Types, Content Items, Rating Models, Model Profiles, DFFs **Goal Management** : Goal Library, Goal Plans, Goal Plan Sets, Lookup, DFFs, Review Period **Performance Management** : Templates, Document Types, Process Flows, Eligibility, Ratings

📁 Project Assets
=================

*   All configuration screenshots are available in the **/screenshots** folder
    
*   Download the project ZIP and unzip to view images (GitHub Raw does not support some JPGs
