---
layout: page
type: text
title: 'Growing the Engineering Team: the Importance of Clean, Tested Code'
date: 2012-03-22
---

The benefits of clean, tested code cannot be underestimated, and writing tests is an essential part of that process.  But when the benefits of testing compete with other considerations, the choice to develop clean, tested code does not always seem so simple.  Perhaps you’re weighing the tradeoffs between writing tests and pumping out the next batch of features to prove a set of hypotheses that, if validated, could indicate your business has legs.  Why write tests or keep code clean in a resource-scarce environment before knowing whether there will even be a business?

If you believe the choice to invest in writing clean, testable code requires difficult tradeoffs like moving fast or writing tests, carefully consider the fact that while moving fast doesn’t necessarily preclude writing clean, tested code, failing to write clean, tested code can introduce significant risk to velocity the moment you need to add engineers to the team.

**So, the next time you’re deciding whether to invest the marginal effort to produce clean, tested code, consider the following in the context of growing your engineering team:**

* Just like smart engineers want to work with other smart engineers, those who have once before worked in a clean, tested codebase will prefer working in a clean, tested codebase.
* Convincing talented engineers to assume the risk of joining your team already carries significant risk – untested spaghetti code is more likely to increase rather than decrease that degree of risk.
* Time is a precious resource, and onboarding additional engineers quickly and efficiently is clearly preferable to onboarding engineers slowly and inefficiently.  Clean, well-tested code significantly reduces ramp-up time: new team members use code as behavior documentation instead of soaking up the time and interrupting the flow of existing team members.
* When an assumption or a choice you made proves to be wrong and your codebase needs refactoring, new team members should have the confidence to make the necessary changes.  When new members refuse to make audacious changes because they’re more concerned about breaking things, the probability that your team is eliciting their true creative and technical potential is far lower than it should be.

Every problem and set of circumstances is different and it is ridiculous to make assertions like “everyone ought to achieve 100% coverage”, or “everyone ought to use unit tests”.  But while projects and circumstances are generally different, most share at least one commonality: successful projects, businesses and teams do eventually need to grow.  As you make decisions, keep considerations like the implications of clean, tested code in the back of your mind so you can efficiently grow your engineering team when the time comes.
