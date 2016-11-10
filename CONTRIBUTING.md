
# Contributing

We welcome all contributions. Discussion happens in the
https://spadwg.slack.com/messages/general/ room in slack and on GitHub
issue threads. Changes are done via git pull requests. For PR merged
into the master branch, we strive for rough consensus and we measure
that view the reviews placed on the PR.

The Specification style is "less is more". If a reasonable developer
who is fully up on modern web development practices could figure out
how write an interoperable implementation after looking at some
examples and code and asking a few questions, well that's good enough
for us. If you can find it on Wikipedia, we don't need to explain it
here.

Markdown is used for text. RAML and JSON Schema are used to describe
the API. Examples are often used as normative specification. The build
chain has the goal is to be simple and obvios with no black magic.


# Published Versions 

The website at TBD provides an overview view of the specification that
is focused on developers. However all the key information to implement
the specification that is used to generate the website is also used to
generate and internet draft that can be found at TBD that is slanted
at specification developers. Periodically the information on the
master is branched to versioned draft branch and published and an
internet draft. A typical cadence for this is monthly so that it can
receiver broader review. If the PRs that were merged to master
represent WG rough consensus, it is expected that it the will move
quickly through the standards process. When the work is at a good
point to form a version of the API, it is progressed to an RFC and the
text of the approved RFC is used to form a released version of the
spec. The first version would be v1. The current working pre standard
version is always referred to as v0.  The API includes the version in
the URL so that developers can implement to a specific non changing
specification. Future versions attempt, but do not guarantee, to be
backwards comptable with the previos version.

