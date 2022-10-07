New Feature: Score

Overview:
The score feature refers to a new form above the comments area in the document view that allows reviewers to add, update, and delete scores for each document. A dropdown menu appears, where the reviewer can select a score of 1 through 5. pressing "submit" will attach that score to the document.

How to use:
  Navigate to the document view
  To the right of the document tabs, there is a "Score" header
  Click on the dropdown menu and select a score, 1 through 5
  Press "Submit" and see the score appear, as well as the name, profile pic of the reviewer, and score timestamp
  Repeat this process to add a new score
  Press the "x" do delete the score from the document
  
How to test:
  Run the test suite to ensure compatibility with all other features
  Modifications to test suite include:
    verify that document has a score parameter in TestDocumentResource
    verify that score has all necessary functionality in TestScoreResource
  A user can manually test by creating a new document, and following the steps in the "How to use" section above
  
  