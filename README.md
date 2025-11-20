---
title: "Team Project Report Instructions"
author: "Joseph Ali"
date: "`r Sys.Date()`"
output:
  html_document:
    
---

## Instructions for Team Members
## Description of the project: 
the f75 data Description: data from a randomized trial testing whether a modified milk formula (f75)  improves outcomes for children with severe acute malnutrition (first 6-months of data from year-long study)

##Team members intrusctions
# DATA 550 Team Project: F75 Interim Dataset

This repository contains data, scripts, and documentation for analyzing the F75 interim dataset, a randomized trial investigating whether modified milk formula improves outcomes for children with severe acute malnutrition. This README provides instructions for team members on building and customizing the team report.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Project Organization](#project-organization)  
3. [Project Workflow and GitHub Instructions](#project-workflow-and-github-instructions)  
4. [Project Structure](#project-structure)  
5. [Report Outline](#report-outline)  
6. [Ground Rules for Team Members](#ground-rules-for-team-members)  

---

## Project Overview

- **Dataset:** F75 Interim Dataset  
- **Type of Data:** Randomized trial  
- **Exposure:** Modified Milk Formula  
- **Outcome:** Malnuturition children 
- **Descriptive Elements:** Sample size, mean ages, weights, etc.

---

## Project Organization

| Role          | Responsibility                          | Deliverable                                      |
|---------------|----------------------------------------|-------------------------------------------------|
| **Group Leader** | Project config file, report parameters | RMarkdown configuration, overall coordination |
| **Coder 1**      | Descriptive statistics (Table 1)       | Code for Table 1 from GitHub                  |
| **Coder 2**      | Visualizations & Graphs                | Code for figures and graphs, tested/merged    |
| **Coder 3**      | Analysis tables                         | Analysis outputs integrated with RMarkdown    |

---

## Project Workflow and GitHub Instructions

1. Each member **forks and clones** the team lead's GitHub repository.  
2. Each coder **integrates their code** in their fork of the repository.  
3. When the code is stable, the coder **submits a pull request** to the team lead.  
4. The team lead **fetches code** from each pull request and runs it locally.  
5. If the code fails, the team lead uses **pull request discussions** to report errors.  
6. Once stable, the team lead **merges** the pull request into the main branch.



## Load the CSV
f75 <- read_csv("data/raw/f75_interim.csv")


