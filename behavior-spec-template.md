*This document is a template for specifying an LDPx behavior.  If you
want to propose a standardized behavior, answer the questions here.
Start small, answering the easier questions, and sharing what you've
produced, until you've gotten positive feedback.  Producing a complete
spec usually involves many conversations with other people, often over
the course of months.*

# LDPx Behavior Specification

## Name 

*Identifier for this behavior/feature/module.  Should match regex [-a-zA-Z0-9]+ and be previously unused, unless this is a successor.   Successors must not be objected to by previous authors.*

## Version Number

*Use semver.   @@ say more about this!*

## Author(s)

## IPR

*(Maybe use W3C Submission language here, for both copyright and patent?)*

# Introduction

## Motivation 

*What problem does this feature solve?  Why would a client software
developer want a server to provide this?  How does the end-user
benefit?*

## Use Cases 

*If possible, include 1-4 true stories of people who want this feature,
possibly including the authors of this specification.  If the people
involved are willing, include the real details, and contact
information to allow corroboration and elucidation.*

## Alternatives

*Are there any other ways the developer could get this functionality or
similar functionality?  How do the different ways compare?  Be sure to
use a neutral point of view -- imagine the people who developed the
alternatives are looking over your shoulder as you write -- and cite
any claims you make in a manner suitable for Wikipedia or an academic
publication.*
       
# Specification

## Protocol

*If applicable, state what conforming server may/must/should do.
Consider including sequence charts, with mscgen source.*

## Browser API

*If application, provide a JavaScript API.  State whether it is
mandatory or just an example.*

## Conformance

*Specify briefly what conformance means.  (Can we leave this out if the
above sections are clear enough?)*

## Unspecified Conditions

*Enumerate any situations intentionally left unspecified above.  This
can happen, for instance, because people cannot reach agreement, or
some aspects of the problem space are not yet well understood.*

# Migration

*This section explains how to operate in a world where only some
servers provide this feature.*

## Detection

*How should application code tell if this feature is available?*

## Fallback Strategies

*Are there ways that applications can degrade gracefully when this
feature is not available?  If a polyfill can provide this feature,
explain details of how it might work.
(Code can go in next section, with rest of example.)*

# Example Client Library

*Excerpt intended for reading by humans.  Omit obvious functions.
Include logic for detection and polyfill, if possible.  Optionally
link to full implementation.*

# Test Suite

## Positive tests

*Provide executable code which will determine if an implementation is
correct in some aspect.  Use ... what framework?  Run in browser
and/or node.js?  Link to directory of tests, or put them here in code
blocks?   Directory, I think.*

## Negative tests

*Provide tests which detect whether an implementation correctly rejects
error conditions, to the extent required by the specification*

## Other tests

*If there are other kinds of tests, describe them and link to them.*

## Related Test Suites

*Describe other related test suites which can be run to further test an
implemention, such a media-type-specific tests*

## Issues

*Enumerate any challenging design issues and describe how they were
settled, or their current state if not settled.  Link elsewhere for
details beyond a paragraph.*

# Evaluation

*Provide a neutral scientific evaluation of how this proposal compares
to the alternatives.  Should at least touch on each of the following
topics.*

## Security

*How does this 

## Privacy

## Accessibility

## I18N

## Performance
