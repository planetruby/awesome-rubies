Awesome Series @ Planet Ruby

[Rubies (Virtual Machines, Compilers, ...)](https://github.com/planetruby/awesome-rubies) • 
[ActiveRecord](https://github.com/planetruby/awesome-activerecord)  •
[Webframeworks (Micro, Macro, APIs, ...)](https://github.com/planetruby/awesome-webframeworks) •
[Events (Conferences, Camps, Meetups, ...)](https://github.com/planetruby/awesome-events) •
[Blogs (News, Opinions, Podcasts, ...)](https://github.com/planetruby/awesome-blogs)


# Rubies

A collection of awesome Rubies (compilers, interpreters, virtual machines, parsers, doc generators, version managers, etc.) 


#### _Contributions welcome. Anything missing? Send in a pull request. Thanks._

Note: :gem: stands for the RubyGems page and :octocat: stands for the GitHub page.


## 3x3 News

**Q: What's 3x3?**

to be done

**Q: What's OptCarrot?**

to be done


### News

- 2017/Dec - [MJIT infrastructure accepted into Ruby 2.6](https://github.com/ruby/ruby/pull/1782) - MJIT infrastructure means: JIT worker thread, profiler, gcc/clang compiler support, loading function from shared object file, some hooks to ensure JIT does not cause SEGV, etc...






## Major Rubies

- [Ruby](https://www.ruby-lang.org), [:octocat:](https://github.com/ruby)- also known as Matz's Ruby Interpreter (MRI) or CRuby; using the YARV (Yet another Ruby VM) since version 1.9 
   - 2017: 2.5  (Dec/24)
   - 2016: 2.4  (Dec/24)
   - 2015: 2.3  (Dec/24)
   - 2014: 2.2  (Dec/24)
- [JRuby](http://jruby.org), [:octocat:](https://github.com/jruby) - Ruby on the Java Virtual Machine (JVM)
   - 2016: v9.1.0.0
   - 2014: v1.7.x
- [Rubinius (rbx)](http://rubini.us), [:octocat:](https://github.com/rubinius) - designed for concurrency; uses a low-pause generational garbage collector; core library and tools coded in Ruby
- [TruffleRuby](https://github.com/graalvm/truffleruby), [:octocat:](https://github.com/graalvm/truffleruby) - A high performance Ruby on top of Truffle and Graal
- [mruby](http://www.mruby.org), [:octocat:](https://github.com/mruby) - lightweight Ruby; designed for linking and embedding within your application

## Minor / Upcoming Rubies

- [Topaz](http://topazruby.com), [:octocat:](https://github.com/topazproject) - Ruby coded in Python on top of RPython (the toolchain that powers PyPy) 
- [GoRuby :octocat:](https://github.com/goruby) - Ruby coded in Go
- [MagLev](http://maglev.github.io), [:octocat:](https://github.com/MagLev) - a ruby interpreter built on top of the GemStone/S (64-bit) Virtual Machine (VM); note - to run MagLev you need a commercial GemStone/S Server (license)
- [tinyrb](http://code.macournoyer.com/tinyrb), [:octocat:](https://github.com/macournoyer/tinyrb) - a tiny subset of Ruby with a Lua'esc Virtual Machine (VM)
- [fruby :octocat:](https://github.com/fruby-lang) - Ruby in Français (French) e.g. classe, défini, si, sinonsi, vrai, faux, fin, etc.

## Discontinued / Rest In Peace (R.I.P.) Rubies 

- [IronRuby](http://ironruby.net), [:octocat:](https://github.com/IronLanguages) - a ruby interpreter built on top of the Microsoft .NET Common Language Runtime (CLR)
- [MacRuby :octocat:](https://github.com/MacRuby) - a ruby interpreter built on top of Apple's Objective-C/Cocoa library
- [Ruby Enterprise Edition (REE)](http://www.rubyenterpriseedition.com) - builds on top of MRI Rubies, versions 1.8.X and later
- [SmallRuby @ České vysoké učení technické v Praze (ČVUT)](https://swing.fit.cvut.cz/projects/smallruby) - a ruby interpreter built on top of the Smalltalk/X virtual machine
- [Diamondback Ruby (DRuby) @ University of Maryland (UMD)](https://www.cs.umd.edu/projects/PL/druby) - adds gradual typing (with type inference and type annotations) to Ruby



## Ruby-to-JavaScript

- [Opal](http://opalrb.org) - [:octocat:](https://github.com/opal), [:gem:](https://rubygems.org/gems/opal) - source-to-source compiler
- [rubys/ruby2js :octocat:](https://github.com/rubys/ruby2js), [:gem:](https://rubygems.org/gems/ruby2js) - minimal yet extensible Ruby to JavaScript converter 
- [RubyJS](http://rubyjs.org/), [:octocat:](https://github.com/rubyjs) - JavaScript standard library based on the Ruby core-lib

## Ruby-to-C (LLVM)

- [Crystal](http://crystal-lang.org), [:octocat:](https://github.com/crystal-lang/crystal) - Ruby-like syntax; statically-typed with type inference; compiles to machine code; run a ye good olde binary

## Ruby-to-Java

- [Mirah](http://www.mirah.org), [:octocat:](https://github.com/mirah) - formerly known as Duby; compiles to Java bytecode; no (extra) runtime library required
- [RubyFlux :octocat:](https://github.com/headius/rubyflux) - a ruby to java static compiler

## Ruby-to-Objective-C/Cocoa

- [RubyMotion](http://www.rubymotion.com) - commercial compiler for Apple iOS/Cocoa

## Ruby-to-Erlang (†)

- [Elixir](http://elixir-lang.org) - Ruby-inspired syntax; a dynamic, functional language for the Erlang VM compiles to BEAM instructions (bytecode)

(†): Note: Elixir is not a Ruby-to-Erlang compiler. Elixir started off with a Ruby-inspired syntax. The language semantics differ e.g. dynamic pure functional vs dynamic general pragmatic "multi-paradigm" language.


## Ruby Version Manager

- [rvm](https://rvm.io), [:octocat:](https://github.com/rvm) - Ruby enVironment Manager; 27,000 lines of shell scripts to manage your rubies (overwrites your cd)
- [rbenv :octocat:](https://github.com/sstephenson/rbenv) - intercepts Ruby commands using shim executables added into your $PATH
- [chruby :octocat:](https://github.com/postmodern/chruby) - changes the current Ruby

## Ruby Language Research, Papers & Books

- [Ruby under a Microscope - An Illustrated Guide to Ruby Internals](http://www.nostarch.com/rum) by Pat Shaughnessy; No Starch Press; 360 pages; Nov 2013
- [Ruby Performance Optimization: Why Ruby Is Slow, and How to Fix It](https://pragprog.com/book/adrpo/ruby-performance-optimization) by Alexander Dymo; The Pragmatic Programmers 
- [The Ruby Bibliography](http://rubybib.org), [:octocat:](https://github.com/rubybib)
- [Streem Lang :octocat:](https://github.com/matz/streem) - prototype of stream based programming language by Yukihiro Matsumoto

## Ruby Benchmarks & Tests

- [RubyBench](http://rubybench.org), [:octocat:](https://github.com/ruby-bench) - Ruby Releases Benchmarks

## Ruby Type Annotations / Signatures

- [Contracts for Ruby (contracts.ruby) :octocat:](https://github.com/egonSchiele/contracts.ruby), [:gem:](https://rubygems.org/gems/contracts) - a contract is one line of code that you write above a method definition; it validates the arguments to the method, and validates the return value of the method
- [Rubype (Ruby+Type) :octocat:](https://github.com/gogotanaka/Rubype), [:gem:](https://rubygems.org/gems/rubype) - gradual type checking for Ruby
- [Typedocs :octocat:](https://github.com/todesking/typedocs), [:gem:](https://rubygems.org/gems/typedocs) - method type annotations for Ruby
- [Typecheck :octocat:](https://github.com/plexus/typecheck), [:gem:](https://rubygems.org/gems/typecheck) - type checking for Ruby methods 
- [Ruby Type Checker (Rtc) :octocat:](https://github.com/plum-umd/rtc)  



## Ruby Stdlib (Core) Extensions / Refinements

- [Active Support :octocat:](https://github.com/rails/rails/tree/master/activesupport), [:gem:](https://rubygems.org/gems/activesupport)
    - [Active Support Core Extensions @ RailsGuides](http://guides.rubyonrails.org/active_support_core_extensions.html) 
- [Zucker :octocat:](https://github.com/janlelis/zucker), [:gem:](https://rubygems.org/gems/zucker) - collection of Ruby refinements; lots of small refinements to sweeten your Ruby code
- [Powerpack :octocat:](https://github.com/bbatsov/powerpack), [:gem:](https://rubygems.org/gems/powerpack) by Bozhidar Batsov et al  - collection of Ruby core extensions for array, enumerable, hash, numeric, string, etc.
- [PowerCore :octocat:](https://github.com/arturoherrero/powercore) by Arturo Herrero et al - collection of Ruby core extensions for array, date, fixnum, hash, kernel, object, proc, string, etc.
 


## Ruby Library Collections

- [SciRuby](http://sciruby.com) - [:octocat:](https://github.com/SciRuby) - tools for scientific computing in Ruby e.g. nmatrix, statsample, etc. 
- [Functional Ruby :octocat:](https://github.com/jdantonio/functional-ruby), [:gem:](https://rubygems.org/gems/functional-ruby) - adding functional programming tools to Ruby; inspired by Erlang, Clojure, Haskell, and Functional Java
- [Concurrent Ruby :octocat:](https://github.com/ruby-concurrency/concurrent-ruby), [:gem:]() - modern concurrency tools including agents, futures, promises, thread pools, supervisors, and more; inspired by Erlang, Clojure, Scala, Go, Java, JavaScript, and classic concurrency patterns



## Ruby Quick References / Cheat Sheets

- [Ruby QuickRef](http://www.zenspider.com/Languages/Ruby/QuickRef.html) - Language, Standard Library, Tools
- [Learn Ruby in Y Minutes](http://learnxinyminutes.com/docs/ruby), [:octocat:](https://github.com/adambard/learnxinyminutes-docs) - A whirlwind tour of Ruby - learnruby.rb

## Ruby Parser / Unparser

- [seattlerb/ruby_parser (RP) :octocat:](https://github.com/seattlerb/ruby_parser), [:gem:](https://rubygems.org/gems/ruby_parser) - a ruby parser written in ruby (using racc -- which does by default use a C extension). RP's output is the same as ParseTree's output: s-expressions using ruby's arrays and base types
- [whitequark/parser :octocat:](https://github.com/whitequark/parser), [:gem:](https://rubygems.org/gems/parser) - a ruby parser written in ruby;  also includes an "unparser" to produce equivalent source code from the parser's Abstract Syntax Tree (AST)s

## Ruby Documentation Generators

- [YARD](http://yardoc.org), [:octocat:](https://github.com/lsegal/yard), [:gem:](https://rubygems.org/gems/yard) - Yay! A Ruby Documentation Tool 
- [SDoc :octocat:](https://github.com/voloko/sdoc), [:gem:](https://rubygems.org/gems/sdoc) - RDoc generator to build searchable HTML documentation for Ruby code
- [RDoc :octocat:](https://github.com/rdoc), [:gem:](https://rubygems.org/gems/rdoc) - RDoc produces HTML and online documentation for Ruby code 

## Ruby Linter / Code Checker / Static Code Analyzer

- [RuboCop :octocat:](https://github.com/bbatsov/rubocop), [:gem:](https://rubygems.org/gems/rubocop) - a Ruby static code analyzer
- [reek :octocat:](https://github.com/troessner/reek), [:gem:](https://rubygems.org/gems/reek) - code smell detector for Ruby
- [RubyCritic :octocat:](https://github.com/whitesmith/rubycritic), [:gem:](https://rubygems.org/gems/rubycritic)


## Ruby Binary Packagers

- [Traveling Ruby](http://phusion.github.io/traveling-ruby), [:octocat:](https://github.com/phusion/traveling-ruby) - self-contained, portable Ruby binaries
- [Omnibus :octocat:](https://github.com/chef/omnibus), [:gem:](https://rubygems.org/gems/omnibus) - mini language (that is, domain-specific language (DSL) for installers (that is, binary packages)

## Ruby Gems / Libraries

- [RubyGems](https://rubygems.org), [:octocat:](https://github.com/rubygems) - 100,000+ Gems
- [Awesome Ruby :octocat:](https://github.com/markets/awesome-ruby)
- [Awesome ActiveRecord :octocat:](https://github.com/planetruby/awesome-activerecord)
- [Awesome Jekyll @ Planet Jekyll :octocat:](https://github.com/planetjekyll/awesome-jekyll)
- [Awesome Markdown :octocat:](https://github.com/writekit/awesome-markdown)
- [Ruby Gem of the Week Series @ Planet Ruby](http://planetruby.github.io/gems), [:octocat:](https://github.com/planetruby/gems)
- [Trending Ruby Projects @ GitHub](https://github.com/trending?l=ruby) - Today, This Week, This Month
- [Alltime Starred Ruby Projects @ GitHub](https://github.com/search?utf8=✓&q=language%3ARuby&type=Repositories&s=stars&l=Ruby)
- [Ruby Toolbox](https://www.ruby-toolbox.com)
- [Gems @ Ruby Bookmarks :octocat:](https://github.com/dreikanter/ruby-bookmarks#gems)


## Ruby Community (Events, Questions & Answers, Announcements, etc.)

- [Ruby @ Reddit](http://www.reddit.com/r/ruby)
- [Awesome Ruby Events :octocat:](https://github.com/planetruby/awesome-events) - meetups, conferences, camps, etc. from around the world 
- [Planet Ruby](http://planetruby.herokuapp.com), [:octocat:](https://github.com/planetruby/planet) - online news reader about all things ruby


## Thanks

Jesse Cooke • Marcel Hlopko • Sota Yamashtia


## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Send them along to the ruby-talk mailing list. Thanks!
