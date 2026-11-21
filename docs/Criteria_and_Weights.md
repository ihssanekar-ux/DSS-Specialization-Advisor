
# Evaluation Criteria and Weights

## 1. Purpose

This document presents the evaluation criteria, their types, and their weights for the Decision Support System for University Specialization Selection.

The system compares university specializations using the Weighted Sum Model (WSM) and uses the resulting scores to rank the alternatives and provide a recommendation.

## 2. Alternatives

The project statement proposes the following university specializations as alternatives:

- **P1:** Artificial Intelligence
- **P2:** Cybersecurity
- **P3:** Data Science
- **P4:** Information Systems and Software Engineering

## 3. Evaluation Criteria

Each specialization is evaluated according to six criteria:

| No. | Criterion | Type | Weight |
|---|---|---|---|
| 1 | Programming | Maximize | 0.20 |
| 2 | Mathematics | Maximize | 0.15 |
| 3 | Alignment with the student's competencies | Maximize | 0.20 |
| 4 | Career opportunities | Maximize | 0.20 |
| 5 | Difficulty | Minimize | 0.10 |
| 6 | Personal interest | Maximize | 0.15 |
| | **Total** | | **1.00** |

The weights sum to **1.00 (100%)**.

## 4. Criterion Types

The criterion type indicates the preferred direction of the evaluation:

- **Maximize:** A higher evaluation value is preferred.
- **Minimize:** A lower evaluation value is preferred.

For the **Difficulty** criterion, the project statement specifies that a higher value means that the specialization is more difficult. Therefore, this criterion is treated as a minimization criterion.

## 5. Evaluation Scale

The performance of each specialization for each criterion is evaluated on a scale from **1 to 10**, as specified in the project statement.

For Difficulty, a higher score represents greater difficulty.

## 6. Weighted Sum Model (WSM)

The project uses the **Weighted Sum Model (WSM)** to evaluate and rank the available specializations.

The process described in the project statement is:

1. Obtain the evaluation value of each specialization for each criterion.
2. Normalize the evaluation values according to the criterion type (Maximize or Minimize).
3. Multiply each normalized value by the corresponding criterion weight.
4. Add the weighted values to obtain the overall score for each specialization.
5. Display the specializations in descending order of their overall scores.
6. Recommend the specialization with the highest overall score.
7. Identify a tie if two or more specializations obtain the same score.

### Normalization Formula

The project statement requires normalization according to criterion type, but it does not specify the exact normalization formula.

The formula to be implemented must therefore be confirmed with the instructor before implementation. No specific formula is assumed in this document.

## 7. Source and Validation Notes

The criteria, criterion types, weights, evaluation scale, and general WSM process in this document are taken from the official DSS final project statement.

The exact normalization formula remains to be confirmed with the instructor.
