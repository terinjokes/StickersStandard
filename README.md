# Sticker Constructor Specification #
> [soon to become a] Living Standard

**Editor**: [Terin Stock][ts-website] <[terinjokes@gmail.com][ts-email]>

[ts-website]: https://terinstock.com
[ts-email]: mailto:terinjokes@gmail.com

## Abstract ##

This specification defines a standard interface for sticker compatibility from multiple vendors.
By following this specification, implementors can ensure they meet the expectations of sticker consumers, and producers can supply tools that integrate with the web platform.

## Status ###

This specification is still a work in progress, as such the term "Living Standard" indicates a goal, rather than a reality.

Several implementors have already experimented with various sizes, shapes and durability as part of the Extensible Web movement.
Please join the [issue tracker][gh-issues] for more discussion.

[gh-issues]: https://github.com/terinjokes/StickerConstructorSpec/issues

## Conformance ##

All diagrams, examples, and notes in this specification are non-normative, as are all sections explicitly marked non-normative.
Everything else in this specification is normative.

The key words "MUST", "MUST NOT", "REQUIRED", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in the normative parts of this specification are to be interpreted as described in [RFC2119][RFC2119].
For readability, these words do not appear in all uppercase letters in this specification.

Conformance requirements phrased as algorithms or specific steps may be implemented in any manner, so long as the end result is equivalent.

[RFC2119]: https://www.ietf.org/rfc/rfc2119.txt

## Square Sticker ##

A **square sticker** must be represented by a square with sides of exactly 5.08 centimeters.

### Integration Behavior ###

## Hexagon Sticker ##

A **hexagon sticker** must be represented by a regular hexagon with the largest diagonals measuring exactly 5.08 centimeters.
The sticker must be oriented with a vertex positioned at the top.

### Integration Behavior ###

## Acknowledgments ##

The editor would like to thank Jason Denizac and Max Ogden for their contributions to this specification.
