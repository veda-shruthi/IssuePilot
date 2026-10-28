# IssuePilot
Explainable AI-Based Software Issue Routing System


# IssuePilot
### Explainable AI-Based Software Issue Routing System

## Overview
IssuePilot is a web-based software issue management prototype
designed to help classify software issue reports, identify
potential duplicate reports, and recommend appropriate
development teams.

## Objectives
- Classify software issues into categories.
- Identify potential duplicate issue reports.
- Recommend a development team for each issue.
- Display prediction confidence and relevant text indicators
  where possible.
- Flag uncertain predictions for human review.
- Support issue tracking, priority management, assignment,
  and status updates.

## Proposed Technology Stack
- Python
- Pandas
- Scikit-learn
- TF-IDF text representation
- Logistic Regression
- Cosine similarity
- Streamlit
- SQLite
- Optional FastAPI backend

## Planned Workflow
1. Prepare and clean labelled software issue reports.
2. Convert issue text into TF-IDF features.
3. Train and evaluate a classification model.
4. Compare reports using cosine similarity.
5. Recommend a team based on the predicted category.
6. Provide explanations and human review for uncertain predictions.
7. Support issue tracking through a dashboard.

## Evaluation
Classification: Precision, Recall, and F1-score.
Duplicate detection: Evaluation using labelled or manually
reviewed examples.
Baseline: Compare classification with a simple keyword-based
approach.

## Project Status
In development. Features and evaluation results will be
documented as they are implemented and tested.
