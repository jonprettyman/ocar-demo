# 1. Record architecture decisions

Date: 2022-09-06

## Status

Proposed

## Context

Engineers, Architects, Project Managers, Product Managers and other stakeholders
have historically had trouble understanding the process around how architecture
decisions get made and where to find details about decisions that have been
made. 

We need to record the architectural decisions that the One Cambia Architecture
Team makes and have a well defined process with visibility supporting them.

## Decision

We will use Architecture Decision Records, as [described by Michael
Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
We will support this with a Jira based process integrated with a github
pull-request flow that supports the lifecycle captured in this [Lucid Chart
diagram](https://lucid.app/lucidchart/19d3e9ef-de3a-4d1a-9a0c-11c578c3cee9/edit?viewport_loc=-136%2C-313%2C3776%2C2328%2C.AENuaccRJqv&invitationId=inv_80acf706-1331-4b11-b211-4335af7a09cf#).


## Consequences

Supporting personnel will have to "learn" yet another collaboration environment
(github) and "lightweight" work process.

Engineers and stakeholders will be able to see decision artifact changes over
time using git based time machine tools (change history, diffs, etc.)

With good commit hygiene and pull request processes, the motivation behind
decisions and changes to decisions should be captured along with the decision.

## More Reading
See Michael Nygard's article, linked above. For a lightweight ADR toolset, see Nat Pryce's [adr-tools](https://github.com/npryce/adr-tools).

See Spotify [Enginnering Blog
post](https://engineering.atspotify.com/2020/04/when-should-i-write-an-architecture-decision-record/)
for a fairly good rationale and some contexts.

See the [Manifesto](../manifesto.pdf)
