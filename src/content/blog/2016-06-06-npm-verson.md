---
title: npm version
pubDatetime: 2016-06-06T00:00:00.000Z
description: npm verson
---

This post mainly refer to the npm dependencies version(ie,the difference between ~ and ^).

In the simplest terms, the tilde matches the most recent minor version (the middle number). ~1.2.3 will match all 1.2.x versions but will miss 1.3.0.

The caret, on the other hand, is more relaxed. It will update you to the most recent major version (the first number). ^1.2.3 will match any 1.x.x release including 1.3.0, but will hold off on 2.0.0.
