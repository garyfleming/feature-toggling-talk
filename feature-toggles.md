theme: Zurich, 1

# Deployment Is Not Release
## From Painful to Perfect

@garyfleming

^	As a developer or project manager, it's not always easy to ensure that multiple features for a project can be built separately. Branching has long been a favoured technique when managing parallel development, but comes at a cost. In this talk, we'll see what that cost is and explore a better alternative. (Hint: it's feature-toggling)



^ Often, when I start working with a new client, I ask people the same question. It's one that I find gets us quickly to some interesting areas to improve.

---

# Where Does it Hurt?

^ TODO toothache pic?

^ Now, I might formulate it slightly different, but the aim is to genuinely try to find things that people hate dealing with. The answers I get with alarming frequency all have something in common.

---

# Where Does it Hurt, Developers?

^ Developers can take a while but often say it's doing a release. That thing they only do once a month, or three months, because it takes all weekend to ensure that it happens correctly. Who wants to spend all weekend at work?

---

# Where Does it Hurt, Testers?

^ Testers often say its knowing what release and features are in each environment. They find it frustrating when they find apparent issues with systems to be dismissed with: "Well, that's not in that environment yet."

---

# Where Does it Hurt, Product Owners?

^ Product Owners often say it's just getting things into the world. Because releases don't happen that often, it takes a long time to deliver the value they promised. Planning becomes difficult because there's a weird rhythm around releases: they take time, make people afraid to make changes that are too big.

---

# Where Does it Hurt, Team?

^ The other thing that everyone said, in some form, was that it bothered them that they couldn't tell whether what they were doing would be useful. Sure, it'd pass the tests, and look about right, and go into production (eventually), but would it deliver the value they had hoped for? Is it what they really needed?

---

# Gain Feedback. Deliver Value.

^ While I could do a full talk on the answers I've had to "Where Does It Hurt?", let's focus on these answers. People want to deliver things of value, but don't have the feedback they need to do that in a timely fashion. That's a problem.

---

# Metathesiophobia: Fear of Change

^ TODO evil clown pic?

^ But underpinning this is also a fear of change. To deliver value and gain feedback, we need to release. Releasing causes pain. We've been hurt enough and don't want hurt again, so we delay it and our feedback along with it. So how do we break this cycle?

---

# Deployment Is Not Release

^ We do it by making deploying software in a continuous and controlled way, such that we can gain feedback without showing everyone.
That is, we make it so that Deployment Is Not Release.

---

# Deployment Is Not Release
## (Roll Credits)

^

---
