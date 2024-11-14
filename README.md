#  FDM-Bench

**FDM-Bench** is a benchmark dataset created to evaluate Large Language Models (LLMs) on Fused Deposition Modeling (FDM)-specific tasks, including G-code anomaly detection, user queries, and multiple-choice questions.

## Dataset Overview

### 1. G-Codes with Labels
- **Anomaly Detection**: Includes G-codes labeled for specific anomalies—Non-defective (ND), Under-extrusion (UE), Over-extrusion (OE), and Spaghetti (SP).
- **Evaluation Types**: Each G-code can be used for both deterministic labeling (single label output) and probability-based labeling.

### 2. Free-Form Questions
- **Expertise Levels**: Questions are categorized by user expertise—Beginner, Experienced, and Theoretical.
- **Sample**: Provided for reference for evaluation consistency.

### 3. Multiple-choice questions (MCQs)
- **Experience Levels**: Similar to free-form questions, with Beginner (B), Experienced(E), and Theoretical (T) levels.
- **Ground Truths**: Answer keys are included to assess model accuracy.

### 4. Prompts
- **Task-Specific Prompts**: Includes prompts for each type of task (G-code detection, free-form responses, and MCQs).

For more detailed information on FDM-Bench and its application, please refer to the accompanying research paper.  
**Cite:** [Soon]
