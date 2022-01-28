**Week 2 Lab Report**
=====================
- ## Fixing Open Paren Inside Link Text
- ![image](lab2pics/openParenChanges.png)
- [openParenTest](https://cmasterm.github.io/cse15l-lab-reports/lab2tests/test-unclosed-open-paren-then-link.md)
- symptom
- ![image](lab2pics/unclodedOpenSymptom.png)
- The bug in the code is that after seing the proper brackets, the code looks for the first open and closed parentheses it can find and returning everything in between.
- Our test case has some improperly formatted links with only open parenthases before a properly formatted link with an open and closed paranthesis
- The symptom is that the improperly formatted links aren't ignored, and that a bunch of formatting garbage with the entire proper link is gathered and returned
