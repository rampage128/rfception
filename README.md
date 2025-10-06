# RFCeption `📝 DRAFT`

> **The definite guide on disrupting modern meeting culture with meaningful collaboration.**

## 1. Abstract

Do you have too many meetings to get much work done? Are you forced to participate in a lot of meetings you can not contribute to or that have no outcome? Did you just have a constructive meeting just to find out that nobody documented anything and now nobody remembers? Are you regularly forced to come up with impromptu solutions for problems that you have just been exposed to in front of a group of people?

If not, congratulations — you're either in a rare, well-structured and well-understood field of work or you've found a loophole. For everyone else, read on.

If you have, then you suffer from the following problems:
- Meetings are a bad format to flesh out complex problems.
- Decisions can not be made without proper preparation.
- Impromptu ideas are not solutions without validation.
- ...
- Your org thinks more talking somehow solves any of the above.

### Don't worry. There is an easy fix.

We can mitigate a lot of issues by collaborating asynchronously to avoid squishing complex ideations into ad-hoc meetings. We can then use meetings for what they are meant to do: Align on actions for a well known problem that has multiple ideas for solution approaches.

## 2. Glossary

- **RFC:** Short for "Request for Comments", which is a short structured proposal document for asynchronous collaboration.
- **Async-first:** Not requiring everyone to be present in real time and allowing for time to think about issues.
- **Work:** Actual work being done as in actually sitting down and creating something as opposed to just talking about it.

## 3. Proposal

We simply adopt RFCs as the standard way to introduce solutions, capture a shared context, organize work and document decisions. We only use meetings to solve conflicts and make decisions based on the findings and ideas inside the RFC.

This RFC aims at providing a template and process to streamline ideation, decision making and organization of (actual) work as well as restoring clinical sanity at the workplace.

## 4. Impact

- ⚠️ Do not use RFCs for trivial, quick exchanges — they're meant for complex discussions only.
- The amount of unfocused meetings is reduced by the async-first approach.
- Contributions have more time to be thought through and validated.
- It is self-documenting and does not rely on someone taking complex notes in a meeting.
- Nobody has to sit in a meeting they can not contribute to.
- Less fragmented schedule for workers, as they can manage their own time.
- Everybody stays on the same page as context of problem, solution and progress is shared and documented.
- Easy onboarding of new participants by sharing the document.
- Post implementation documentation (in case anyone wants to do forensics).

## 5. Template & Usage

Take the markdown template below, paste it into whatever documentation tool you have and adjust to fit your personal RFC:


```md
# RFC Title `[STATUS]`
<!-- Pick a Status: 📝 DRAFT | 💬 UNDER DISCUSSION | ✅ ACCEPTED | 🚫 REJECTED | 🚀 IMPLEMENTED -->
> **TL;DR: [One-sentence executive summary]**

## 1. Abstract

<!-- 1-2 paragraphs explaining the problem and context. -->

## 2. Glossary <!-- OPTIONAL -->

<!-- Optional bullets to define terms that are very specific or might be misunderstood. 
Remove if you do not have anything to declare. -->

## 3. Proposal

<!-- What's the solution idea? Why do we do it? -->

## 4. Impact

<!-- Short bullet points to signify who/what is affected with a sprinkle of pros and cons. -->

## 5. Details

<!-- This outlines the work that has to be done. 
It can be technical details, user flows, diagrams or examples (very much like this one).
The headline can be changed to accommodate the content (i.e.: Flow, implementation, Database layout, ...) -->

## 6. Alternatives Considered

<!-- Short bullets on alternatives (if available with a link to documentation).
Also potentially include a status: `🚫 Rejected | 📉 Inferior | 🚧 Unfeasible`. -->
```


In order to keep a focused and efficient flow consider the following criteria:
- The document should make clear what it is about as quickly and clearly as possible.
- It should describe the problem and propose a solution, outlining the Impact
- The Implementation part should only be as detailed as it **has to be**. 
- **This is not an academic paper you are writing.**
- Your document should be inside a tool that allows readers to comment/collaborate on it in some way (duh!).

## 6. Alternatives Considered
- **Rely on jira tickets:** `🚧 Unfeasible` Jira tickets are bad for creative collaboration. They serve as working instructions and progress documentation. 
- **Rely on slack**: `📉 Inferior` Can be helpful for discussions, but is bad for documentation and tends to become noisy. 
- **jira __and__ slack:** `📉 Inferior` [insert more random tools]: Hey, we talked about this topic in the past... where was that again? (too fragmented) 
- **More meetings:** `🚫 Rejected` God, please no! 

## 7. Breaking the Fourth Wall (Meta section)

Every workplace is different... You might find yourself in a situation where this RFC solution would be helpful, but for different reasons. Or your company might prefer a different communication style and wording for such documents.

**If you want your own variant of this reference RFC, feel free to fork and edit the RFC to fit your individual situation, and remove the Meta section from your fork.**
