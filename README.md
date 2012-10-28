Mini Frameworks are extremely useful tiny frameworks which are entirely self contained.



Why Mini?
---------

- They are laser focused.

  Use only what you need. No big libraries with tons of unknown classes running in your project. There's much less to learn and figure out.
  
- They are easier to build off of and combine.

  When possible, Mini Frameworks strive to add functionality in a general way. For example, creating categories on and returning standard Cocoa classes rather than custom subclasses. This way they can be helpful to as much code as possible.

- They are easier to customize.
  
  Sometimes a framework just doesn't perfectly fit into your project or lacks a small project specific feature. Because Mini frameworks are designed to tackle one small idea each, they are easier to customize. Copy, customize code, and change class names without fear of breaking a large library.



Creating Your Own
-----------------

Mini Frameworks should try to tackle a single idea. Typically, they should have at most one external class and limit the number of methods as much as possible.

- Each mini framework may consist of at most 2 files (a header and an implementation).
- A mini framework may not include other files with the exception of system frameworks and files. (*Mini Framework subclasses, though discouraged, may include their superclass*).
- (Optional) A mini framework may contain a one line description/comment of this form: `// @mf: A one line description`. The `describe.rb` script scrapes these descriptions from mini frameworks.



Thoughts
--------

I hope you find Mini Frameworks useful for certain situations, I know I do. Please let me know what you like and don't like about Mini Frameworks. I am always open to suggestions and I still have a lot to learn.

Thanks,  
Jason







