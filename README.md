# Google Summer of Code 2022

## Organization: CNCF (TUF Project)

As a Google Summer of Code 2022 mentee, I worked on the [TUF project](https://github.com/theupdateframework/python-tuf) under my mentors [Marina Moore](https://github.com/mnm678) and [Zach Newman](https://github.com/znewman01) (co-advising) to implement [TAP 14](https://github.com/theupdateframework/taps/blob/master/tap14.md). This included implementing version management for TUF’s python reference implementation. The implementation does not currently have a way to migrate TUF repositories or clients to a new TUF version that has breaking changes. This project will be the implementation of a proposal for coordinating specification versions between a repository and a client to prevent interruptions in access to updates after a major version change to the specification.

## Goals achieved

- Setting up sample test files for future tests 
- Add tests to check for the test files
- Add the functionality to get the list of specification versions supported by the repository
- Add the functionality to choose the highest matching version between the repository and the client
- Add tests for checking the functionality to get the highest matching version
- Worked on implementing further changes through the review process

## Work remaining

- Adding tests to check the functionality of getting specification versions supported by the repository
- Working on the special cases

## TAP 14 draft pr

https://github.com/theupdateframework/python-tuf/pull/2049 

## Summary
Had a lot of fun working on implementing changes and learning a lot in the process. 👍
