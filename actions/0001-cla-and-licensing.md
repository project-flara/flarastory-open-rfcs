- Feature Name: Implement CC-BY-SA 4.0 or CC-BY-SA-ND 4.0 and Harmony CLA
- Start Date: 2022-12-15
- RFC PR: [project-flara/flarastory-open-rfcs#0002](https://github.com/project-flara/flarastory-open-rfcs/pulls/0002)

# Summary
[summary]: #summary

Implement a policy to license all story contributions under CC-BY-SA 4.0 or CC-BY-SA-ND 4.0 with Harmony CLA. 

# Motivation
[motivation]: #motivation

We might not want to license the story under the same license of the main code: MIT OR APACHE-2.0.
While for code it allows for more corporate adoption of our codebase, but making a story under a permissive license would make it open to open source plagiarism I guess.
It's good when community members create zines, artworks, or fanstories based of our IPs, even if they are also for-profit, but what about people that don't make them because they love our IPs but just want the profit?
Because of this concern I think it's necessary to have a more stricter license.

# Guide-level explanation
[guide-level-explanation]: #guide-level-explanation

Here is the licensing guide:
- Story plots directly embedded to Project Flara (its main story, etc) -> CC-BY 4.0, CC-BY-SA 4.0, or CC-BY-SA N.D 4.0
- Signing the CLA is optional.
- Story plots for collabs with pre-established IPs -> Custom terms (since we're touching other IPs)

Licensing should be clear and concise. There should be no confusion on what license is a dialog or a chapter is licensed under. 
Story plots that use "non-commercial use" license can still be merged without CLA, but that means less flexibility for us to adopt in collabs or perhaps merchandises, without prior agreement with the authors.
ND licenses might also restrict the practice of for-profit fandom economy, which to be fair we should be for it, as they're usually small businesses pretty much!
# Reference-level explanation
[reference-level-explanation]: #reference-level-explanation
Not needed

# Drawbacks
[drawbacks]: #drawbacks

Why should we *not* do this?

# Rationale and alternatives
[rationale-and-alternatives]: #rationale-and-alternatives

- Why is this design the best in the space of possible designs?
- What other designs have been considered and what is the rationale for not choosing them?
- What is the impact of not doing this?
- If this is a language proposal, could this be done in a library or macro instead? Does the proposed change make Rust code easier or harder to read, understand, and maintain?

# Prior art
[prior-art]: #prior-art

Discuss prior art, both the good and the bad, in relation to this proposal.
A few examples of what this can include are:

- For language, library, cargo, tools, and compiler proposals: Does this feature exist in other programming languages and what experience have their community had?
- For community proposals: Is this done by some other community and what were their experiences with it?
- For other teams: What lessons can we learn from what other communities have done here?
- Papers: Are there any published papers or great posts that discuss this? If you have some relevant papers to refer to, this can serve as a more detailed theoretical background.

This section is intended to encourage you as an author to think about the lessons from other languages, provide readers of your RFC with a fuller picture.
If there is no prior art, that is fine - your ideas are interesting to us whether they are brand new or if it is an adaptation from other languages.

Note that while precedent set by other languages is some motivation, it does not on its own motivate an RFC.
Please also take into consideration that rust sometimes intentionally diverges from common language features.

# Unresolved questions
[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

# Future possibilities
[future-possibilities]: #future-possibilities

Think about what the natural extension and evolution of your proposal would
be and how it would affect the language and project as a whole in a holistic
way. Try to use this section as a tool to more fully consider all possible
interactions with the project and language in your proposal.
Also consider how this all fits into the roadmap for the project
and of the relevant sub-team.

This is also a good place to "dump ideas", if they are out of scope for the
RFC you are writing but otherwise related.

If you have tried and cannot think of any future possibilities,
you may simply state that you cannot think of anything.

Note that having something written down in the future-possibilities section
is not a reason to accept the current or a future RFC; such notes should be
in the section on motivation or rationale in this or subsequent RFCs.
The section merely provides additional information.
