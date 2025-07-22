Project: Short Answer Evaluation

This Git file contains the source code and logic for a short answer evaluation system that leverages natural language processing (NLP) techniques to assess and score student responses in Java and Python programming topics. The project combines a user-friendly graphical interface with both keyword matching and semantic similarity algorithms to provide automated, nuanced evaluation of short, open-ended answers[1].

Key Features:

- Tkinter-based GUI: Interactive interface for navigating questions, entering answers, and viewing evaluation results.
- Language Selection: Separate modules for evaluating Java and Python answers via a dedicated main menu.
- Database Integration: Fetches questions and reference answers directly from a MySQL database.
- Answer Evaluation:
  - Preprocessing: Tokenizes, lowercases, removes stopwords and punctuation.
  - Keyword Match: Calculates the overlap between the student’s and reference answer’s key terms.
  - Semantic Similarity: Uses TF-IDF and cosine similarity to evaluate conceptual alignment.
  - Combined Scoring: Blends keyword and semantic scores for a final, balanced evaluation.
- Session Management: Stores user responses and evaluation results per question, with navigation between previous and next questions.
- Result Summary: Generates a comprehensive summary of all evaluated answers at session end, including keyword score, semantic score, and final score for each response.

Typical Usage:

1. Launch the application and select the programming language (Java or Python).
2. Answer each question presented, navigating with Prev and Next buttons.
3. After completing all questions, view the Final Evaluation Summary, which details scoring and comparison to reference answers.

Dependencies:
- Python 3
- Tkinter
- NLTK
- scikit-learn
- numpy
- mysql-connector-python

This tool is designed for educational contexts needing objective, automated short answer scoring, particularly in programming assessments[1].

