# SynchronizedXMLParser
A subclass of the standard NSXMLParser from Cocoa that helps you avoid unintended reentrant parsing (basically, that means "avoid crashes on iOS 8").
If the question is "Why is it helpful?", please see:
- http://stackoverflow.com/questions/25642070/nsxmlparser-on-ios8-nsxmlparser-does-not-support-reentrant-parsing
- http://stackoverflow.com/questions/25363560/ios8-nsxmlparser-crash
- http://stackoverflow.com/questions/26880286/xcode-6-1-ios-8-1-crashing-nsxmlparser-does-not-support-reentrant-parsing
- http://stackoverflow.com/questions/25277430/xmlparser-parse-lead-to-crash-in-ios8-but-work-fine-in-ios-7

This repository contains only one .swift file and is straightforward and simple to use:
- You just copy it into your project and
- Use instances of SynchronizedXMLParser as if they are of NSXMLParser.
No additional efforts required, just profit :)

P. S. The content of the .swift file is absolutely free of any kind of license. Please feel free to use as is, modify and distribute it in any form. A reference to the author would be much appreciated though.
