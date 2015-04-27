Quizzer is a sample project composed of 3 sub modules:

  * <b>quizzerwebapp</b>:
A full web application powered by <b>Struts</b>, <b>Hibernate</b>, <b>Spring</b>, that allows you to educate yourself by answering to questions in several categories, just like a quiz. You don't need to be registered to play the game. But if you are, you can in addition propose your own categories, questions, vote for a category / question, have your results saved after each game, ...

![http://quizzer.googlecode.com/svn/wiki/images/quizzerwebapp/screen_home_en.png](http://quizzer.googlecode.com/svn/wiki/images/quizzerwebapp/screen_home_en.png)

  * <b>quizzeradmin</b>:
A rich internet application powered by <b>GWT</b>. It allows administrators to monitor   the Quizzer web application activity: validating or deleting categories and/or questions proposals, deleted old users, creating new categories, questions, etc.

![http://quizzer.googlecode.com/svn/wiki/images/quizzeradmin/screen_welcome.png](http://quizzer.googlecode.com/svn/wiki/images/quizzeradmin/screen_welcome.png)

  * <b>quizzermodel</b>:
Quizzer model contains data shared by the two previous projects.


The project uses <b>Maven</b> as a build and dependencies management system.