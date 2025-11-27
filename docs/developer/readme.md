# Developer

## Communication

In addition to the options in [Community](../../community), there are also some developer-specific channels for communication.

The primary communication method for GNUstep is the mailing lists.

- gnustep-dev: general developer discussion.
- bug-gnustep: submit bug reports and patches.

Every second Saturday we hold an open [Jitsi meeting](https://meet.jit.si/GNUstepOfficial) at 15:30 - 18:30 UTC. **TODO** Use our calendar invite to set a reminder in your local time zone.

## APIs

Our APIs are split into three main libraries:
- base: known as Foundation in Cocoa, base is the core of GNUstep; which can also be used to build CLI/server apps.
- gui: known as AppKit in Cocoa, gui is a UI toolkit that tells the app what to draw.
- back: the brains behind gui, back tells the app how to draw graphics.

More details on the architecture of GNUstep can be found in [About](../../about).

## Objective-C

The preferred programming language, and what our libraries are written in, is Objective-C. Other programming languages can be used to create the logic code for apps, but the UI code must be implemented in Objective-C.

A strict superset of C, Objective-C simply adds object-oriented programming concepts on top of C. Though the syntax may appear foreign at first, it's easy to learn since it's so small. The way that it reads shows off one its strengths: self-documenting code. It is mature and stable, not changing frequently; so you can rest assured that the software you write with it won't be high maintenance and will stand the test of time.

To use Objective-C 2.0 features such as ARC (Automatic Reference Counting), blocks, and fast enumeration, use Clang as your compiler. For maximum portability, compile using GCC.

### Resources

One of the best ways to learn is to read a book.

If you don't quite have the time to read a book, videos can be a quick way to get into the topic.

If you have the basics down, articles can help deepen your understanding.

#### Beginner

If you're new to programming, K. N. King's _C Programming: A Modern Approach_ is a good introduction with exercises to help reinforce the concepts. If you have experience with programming, but not C, _The C Programming Language_ by Brian W. Kernighan and Dennis M. Ritchie is the classic text on C.

Objective-C is a mature, stable language with many existing materials available. Almost any Objective-C or Cocoa (Foundation or AppKit) resource can be applied to GNUstep. Notable exceptions include **TODO**.

**Books**
- Objective-C ... Aaron Hillegass
- Cocoa ... Aaron Hillegass

**Videos**
- [Objective-C Essential Training](TODO) by Simon Allardice
- [Cocoa Essential Training](https://archive.org/details/cocoa-essential-training) by Simon Allardice

**Articles**
- Apple's Objective-C Programming...
- Apple's Cocoa Introduction...

#### Intermediate

**Books**
- O'Reilly...

**Videos**
- WWDC Videos... **TODO**

**Articles**
- Apple's Developer Reference...
- [NSArray](articles/nsarray) (from CocoaDev)
- [NSFastEnumeration / NSEnumerator](articles/nsfastenumeration-nsenumerator) (from NSHipster)
- NSBlog (Mike Ash's Blog)

#### Advanced

**Videos**
- WWDC Videos... **TODO**

#### Developer API Reference

Since our official API reference documentation is not yet complete, a good starting point is a web archive of Apple's [Mac Developer Library](https://web.archive.org/web/20150701093557/https://developer.apple.com/library/mac/navigation/) or the current archive for [Foundation](https://developer.apple.com/library/archive/navigation/#section=Technologies&topic=Foundation) and [AppKit](https://developer.apple.com/library/archive/navigation/#section=Technologies&topic=AppKit).

- [Base Library API](https://www.gnustep.org/resources/documentation/Developer/Base/Reference/index.html)
- [Base Additions API](https://www.gnustep.org/resources/documentation/Developer/BaseAdditions/Reference/index.html)
- [GUI Library API](https://www.gnustep.org/resources/documentation/Developer/Gui/Reference/index.html)
- [GUI Additions API](https://www.gnustep.org/resources/documentation/Developer/Gui/Additions/index.html)
