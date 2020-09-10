[Jump straight to the methodology, hosted in this repo's wiki](https://github.com/tprynn/web-methodology/wiki).

# About the methodology

A methodology document aims to enumerate all the possible areas which need to be reviewed during a security assessment. As a tool, security testers can learn from the document and use it to shape their testing process. It can also be used by developers to understand what types of vulnerabilities may exist in their applications and the best practices they should implement to reduce the risk of attacks.

# Goals of the methodology

The goal of this methodology is to be as effective as possible in communicating what issues to test for, why that issue matters, and (where possible) provide recommendations on how to efficiently test for and remediate the issue. The guiding principles I follow when writing the document are:

**Flexibility, Reliability, Usability**: The document should be kept up-to-date and usable across a wide range of different applications. If the methodology focuses too heavily on specific technologies or frameworks, readers won't be sure whether a given issue applies to their situation. It should be usable by less-experienced readers (to provide an introduction to what modern security testing looks like) and highly-experienced readers (to keep them up-to-date and help ensure they achieve full coverage).

**Be Succinct**: The document should be as succinct as possible in explaining each category or issue. Get straight to the heart of the matter and provide high-quality references when needed for more information. Avoid bloating the document with information on any single issue, when one issue is only a small portion of the entire document.

**Be Opinionated**: Don't shy away from clearly stating best practices. Even more importantly, do not attempt to cover every possible security issue - especially when an issue has minimal or no impact in most situations. If an issue has a range of acceptable recommendations, make a secure, widely-applicable suggestion and rely on the reader to combine this with their specific context.

Ultimately, no methodology is a substitute for the judgment of an experienced tester who can take into account the context of their specific application. A home-grown embedded HTTP server written in C will have very different vulnerabilities than a Kubernetes microservice using the latest web framework with a React frontend. This document defines a baseline which can be used by anyone interested in improving the security of web applications, and serves as a standard which testers can hold themselves to in order to deliver high-quality results.
