# Review process

## Purpose

We are all here to learn. But learning is not isolated to coding concepts. Soft skills in software engineering are incredibly important. Thusly, we emphasize the review process. In short there will be written and verbal reviews for each project. Both formal and informal recommendations. The initial review will be the written review on a peer's project. These will be assigned on a rotating basis. Each member must complete their assigned written review. They may also review more if they are so inclined. The informal feedback will happen during the weekly meeting while each member presents their project and discusses details about it.

## Written reviews

Each member will submit a PR to the project's repo by day 5. This will allow for the reviewer to review the PR before the weekly meeting. Written reviews should focus on a few specific areas.

### Meets project requirements

This seems obvious. But someone working on a project may get caught out in the weeds and forget to follow through on a requirement. This is just making sure the project ticks all the boxes. If it does great, if not just letting them know what they missed.

### Code quality

The term 'high quality code' is throw around quite a bit. This is a chance to show what a bit of refactoring here and there can accomplish. Some things to look for are comments on code where another developer might be confused, contrary to popular belief, code is not self documenting. This is also referred to as 'readability'. Since you are looking at it with fresh eyes, anything that confuses you would likely confuse someone else looking at it. Make note of this confusion and how long it takes you to figure out. Let your peer know in a constructive way what your initial thoughts were when looking at their project. If you see areas where code could be cleaned up, abstracted ([for good reason](https://kentcdodds.com/blog/aha-programming)), or tightened down, let them know. Adding links to articles, or references on methods they could have used would be a really nice touch. This would also be a time to measure the code's complexity. Sometimes we get carried away and code golf our way into something that it too complex to reason about. There are tools available to measure [cyclomatic complexity](https://eslint.org/docs/rules/complexity) that may offer some good insights.

### Above and beyond

If the project you're reviewing went above and beyond, perhaps hitting some of the project's bonus requirements. Be sure to point that out. This is clearly someone who wears more than the bare minimum 14 pieces of flare and they should be recognized for it!

## Weekly meetings

just a few guidelines here:

- start out with the project description and requirements
- everyone should share their project and get feedback from other members
- discuss what was learned in the process
- discuss what you didnt enjoy about the project (pain points)
- conclude the meeting introducing the next cycle's project
