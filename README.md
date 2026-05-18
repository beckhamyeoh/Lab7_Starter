Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed. This is because it guarantees that the tests actually run. Running on every push catches unwanted bugs immediately and we know exactly which file the bug is from. Also, by testing immediately, we remove the risk of forgetting to test later in the future.

Would you use an end to end test to check if a function is returning the correct output?
No.

What is the difference between navigation and snapshot mode?
Navigation analyzes a page right after it loads, while snapshot mode analyzes a page in its current state.

Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
1. Reduce unused JavaScript
2. add a [lang] attribute to the <html> element
3. add a meta description to the Document

