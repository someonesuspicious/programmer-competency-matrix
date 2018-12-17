#Programmer Competency Matrix

<table>
<tbody>
<tr>
<th colspan="5">A. Computer Science</th>
</tr>
<tr class="headers">
<td></td>
<td>Level 1</td>
<td>Level 2</td>
<td>Level 3</td>
<td>Level 4</td>
</tr>
<tr>
<td>1. data structures</td>
<td>Doesn’t know the difference between Array and LinkedList</td>
<td><b>Able to explain and use Arrays, LinkedLists, Dictionaries etc in practical programming tasks</b></td>
<td>Knows space and time tradeoffs of the basic data structures, Arrays vs LinkedLists, Able to explain how hashtables can be implemented and can handle collisions, Priority queues and ways to implement them etc.</td>
<td>Knowledge of advanced data structures like B-trees, binomial and fibonacci heaps, AVL/Red Black trees, Splay Trees, Skip Lists, tries etc.</td>
</tr>
<tr>
<td>2. algorithms</td>
<td>Unable to find the average of numbers in an array</td>
<td><b>Basic sorting, searching and data structure traversal and retrieval algorithms</b></td>
<td>Tree, Graph, simple greedy and divide and conquer algorithms, is able to understand the relevance of the levels of this matrix.</td>
<td>Able to recognize and code dynamic programming solutions, good knowledge of graph algorithms, good knowledge of numerical computation algorithms, able to identify NP problems etc.</td>
</tr>
<tr>
<td>3. systems programming</td>
<td>Doesn’t know what a compiler, linker or interpreter is</td>
<td>Basic understanding of compilers, linker and interpreters. Understands what assembly code is and how things work at the hardware level. Some knowledge of virtual memory and paging.</td>
<td>Understands kernel mode vs. user mode, multi-threading, synchronization primitives and how they’re implemented, able to read assembly code. Understands how networks work, understanding of network protocols and socket level programming.</td>
<td><b>Understands the entire programming stack, hardware (CPU + Memory + Cache + Interrupts + microcode), binary code, assembly, static and dynamic linking, compilation, interpretation, JIT compilation, garbage collection, heap, stack, memory addressing…</b></td>
</tr>
<tr>
<th colspan="5"> B. Software Engineering</th>
</tr>
<tr>
<td>4. source code version control</td>
<td>Folder backups by date</td>
<td>VSS and beginning CVS/SVN user</td>
<td>Proficient in using CVS and SVN features. Knows how to branch and merge, use patches setup repository properties etc.</td>
<td><b>Knowledge of distributed VCS systems. Has tried out</b> Bzr/Mercurial/Darcs/<b>Git</b></td>
</tr>
<tr>
<td>5. build automation</td>
<td>Only knows how to build from IDE</td>
<td><b>Knows how to build the system from the command line</b></td>
<td>Can setup a script to build the basic system</td>
<td>Can setup a script to build the system and also documentation, installers, generate release notes and tag the code in source control</td>
</tr>
<tr>
<td>6. automated testing</td>
<td>Thinks that all testing is the job of the tester</td>
<td><b>Has written automated unit tests and comes up with good unit test cases for the code that is being written</b></td>
<td>Has written code in TDD manner</td>
<td>Understands and is able to setup automated functional, load/performance and UI tests</td>
</tr>
<tr>
<th colspan="5">C. Programming</th>
</tr>
<tr>
<td>7. problem decomposition</td>
<td>Only straight line code with copy paste for reuse</td>
<td>Able to break up problem into multiple functions</td>
<td>Able to come up with reusable functions/objects that solve the overall problem</td>
<td><b>Use of appropriate data structures and algorithms and comes up with generic/object-oriented code that encapsulate aspects of the problem that are subject to change.</b></td>
</tr>
<tr>
<td>8. systems decomposition</td>
<td>Not able to think above the level of a single file/class</td>
<td>Able to break up problem space and design solution as long as it is within the same platform/technology</td>
<td><b>Able to design systems that span multiple technologies/platforms.</b></td>
<td>Able to visualize and design complex systems with multiple product lines and integrations with external systems. Also should be able to design operations support systems like monitoring, reporting, fail overs etc.</td>
</tr>
<tr>
<td>9. communication</td>
<td>Cannot express thoughts/ideas to peers. Poor spelling and grammar.</td>
<td>Peers can understand what is being said. Good spelling and grammar.</td>
<td>Is able to effectively communicate with peers</td>
<td><b>Able to understand and communicate thoughts/design/ideas/specs in a unambiguous manner and adjusts communication as per the context</b></td>
</tr>
<tr>
<td>10. code organization within a file</td>
<td>no evidence of organization within a file</td>
<td>Methods are grouped logically or by accessibility</td>
<td><b>Code is grouped into regions and well commented with references to other source files</b></td>
<td>File has license header, summary, well commented, consistent white space usage. The file should look beautiful.</td>
</tr>
<tr>
<td>11. code organization across files</td>
<td>No thought given to organizing code across files</td>
<td>Related files are grouped into a folder</td>
<td>Each physical file has a unique purpose, for e.g. one class definition, one feature implementation etc.</td>
<td><b>Code organization at a physical level closely matches design and looking at file names and folder distribution provides insights into design</b></td>
</tr>
<tr>
<td>12. source tree organization</td>
<td>Everything in one folder</td>
<td><b>Basic separation of code into logical folders.</b></td>
<td>No circular dependencies, binaries, libs, docs, builds, third-party code all organized into appropriate folders</td>
<td>Physical layout of source tree matches logical hierarchy and organization. The directory names and organization provide insights into the design of the system.</td>
</tr>
<tr>
<td>13. code readability</td>
<td>Mono-syllable names</td>
<td>Good names for files, variables classes, methods etc.</td>
<td><b>No long functions, comments explaining unusual code, bug fixes, code assumptions</b></td>
<td>Code assumptions are verified using asserts, code flows naturally – no deep nesting of conditionals or methods</td>
</tr>
<tr>
<td>14. defensive coding</td>
<td>Doesn’t understand the concept</td>
<td>Checks all arguments and asserts critical assumptions in code</td>
<td><b>Makes sure to check return values and check for exceptions around code that can fail.</b></td>
<td>Has his own library to help with defensive coding, writes unit tests that simulate faults</td>
</tr>
<tr>
<td>15. error handling</td>
<td>Only codes the happy case</td>
<td>Basic error handling around code that can throw exceptions/generate errors</td>
<td><b>Ensures that error/exceptions leave program in good state, resources, connections and memory is all cleaned up properly</b></td>
<td>Codes to detect possible exception before, maintain consistent exception handling strategy in all layers of code, come up with guidelines on exception handling for entire system.</td>
</tr>
<tr>
<td>16. IDE</td>
<td>Mostly uses IDE for text editing</td>
<td>Knows their way around the interface, able to effectively use the IDE using menus.</td>
<td><b>Knows keyboard shortcuts for most used operations.</b></td>
<td>Has written custom macros</td>
</tr>
<tr>
<td>17. API</td>
<td><b>Needs to look up the documentation frequently</b></td>
<td>Has the most frequently used APIs in memory</td>
<td>Vast and In-depth knowledge of the API</td>
<td>Has written libraries that sit on top of the API to simplify frequently used tasks and to fill in gaps in the API</td>
</tr>
<tr>
<td>18. frameworks</td>
<td>Has not used any framework outside of the core platform</td>
<td>Has heard about but not used the popular frameworks available for the platform.</td>
<td><b>Has used more than one framework in a professional capacity and is well-versed with the idioms of the frameworks.</b></td>
<td>Author of framework</td>
</tr>
<tr>
<td>19. requirements</td>
<td>Takes the given requirements and codes to spec</td>
<td>Come up with questions regarding missed cases in the spec</td>
<td><b>Understand complete picture and come up with entire areas that need to be speced</b></td>
<td>Able to suggest better alternatives and flows to given requirements based on experience</td>
</tr>
<tr>
<td>20. scripting</td>
<td>No knowledge of scripting tools</td>
<td>Batch files/shell scripts</td>
<td>Perl/Python/Ruby/VBScript/Powershell</td>
<td><b>Has written and published reusable code</b></td>
</tr>
<tr>
<td>21. database</td>
<td>Thinks that Excel is a database</td>
<td>Knows basic database concepts, normalization, ACID, transactions and can write simple selects</td>
<td><b>Able to design good and normalized database schemas keeping in mind the queries that’ll have to be run, proficient in use of views, stored procedures, triggers</b> and user defined types. <b>Knows difference between clustered and non-clustered indexes. Proficient in use of ORM tools.</b></td>
<td>Can do basic database administration, performance optimization, index optimization, write advanced select queries, able to replace cursor usage with relational sql, understands how data is stored internally, understands how indexes are stored internally, understands how databases can be mirrored, replicated etc. Understands how the two phase commit works.</td>
</tr>
<tr>
<th colspan="5">D. Experience</th>
</tr>
<tr>
<td>22. languages with professional experience</td>
<td>Imperative or Object Oriented</td>
<td><b>Imperative, Object-Oriented and declarative (SQL), added bonus if they understand static vs dynamic typing, weak vs strong typing and static inferred types</b></td>
<td>Functional, added bonus if they understand lazy evaluation, currying, continuations</td>
<td>Concurrent (Erlang, Oz) and Logic (Prolog)</td>
</tr>
<tr>
<td>domain knowledge</td>
<td>No knowledge of the domain</td>
<td>Has worked on at least one product in the domain.</td>
<td><b>Has worked on multiple products in the same domain.</b></td>
<td>Domain expert. Has designed and implemented several products/solutions in the domain. Well versed with standard terms, protocols used in the domain.</td>
</tr>
<tr>
<th colspan="5">E. Knowledge</th>
</tr>
<tr>
<td>25. tool knowledge</td>
<td>Limited to primary IDE (VS.Net, Eclipse etc.)</td>
<td>Knows about some alternatives to popular and standard tools.</td>
<td><b>Good knowledge of editors, debuggers, IDEs, open source alternatives etc. etc. For e.g. someone who knows most of the tools from Scott Hanselman’s power tools list. Has used ORM tools.</b></td>
<td>Has actually written tools and scripts, added bonus if they’ve been published.</td>
</tr>
<tr>
<td>26. languages exposed to</td>
<td>Imperative or Object Oriented</td>
<td><b>Imperative, Object-Oriented and declarative (SQL), added bonus if they understand static vs dynamic typing, weak vs strong typing and static inferred types</b></td>
<td>Functional, added bonus if they understand lazy evaluation, currying, continuations</td>
<td>Concurrent (Erlang, Oz) and Logic (Prolog)</td>
</tr>
<tr>
<td>28. knowledge of upcoming technologies</td>
<td>Has not heard of the upcoming technologies</td>
<td>Has heard of upcoming technologies in the field</td>
<td><b>Has downloaded the alpha preview/CTP/beta and read some articles/manuals</b></td>
<td>Has played with the previews and has actually built something with it and as a bonus shared that with everyone else</td>
</tr>
<tr>
<td>29. platform internals</td>
<td>Zero knowledge of platform internals</td>
<td><b>Has basic knowledge of how the platform works internally</b></td>
<td>Deep knowledge of platform internals and can visualize how the platform takes the program and converts it into executable code.</td>
<td>Has written tools to enhance or provide information on platform internals. For e.g. disassemblers, decompilers, debuggers etc.</td>
</tr>
<tr>
<td>30. books</td>
<td><b>Head first series</b>, Unleashed series, 21 days series, 24 hour series, dummies series…</td>
<td>Code Complete, Don’t Make me Think, Mastering Regular Expressions</td>
<td><b>Design Patterns</b>, Peopleware, <b>Programming Pearls</b>, Algorithm Design Manual, <b>Pragmatic Programmer</b>, Mythical Man month</td>
<td>Structure and Interpretation of Computer Programs, Concepts Techniques, Models of Computer Programming, Art of Computer Programming, Database systems , by C. J Date, Thinking Forth, Little Schemer</td>
</tr>
<tr>
<td>31. blogs</td>
<td>Has heard of them but never got the time.</td>
<td><b>Reads tech/programming/software engineering blogs and listens to podcasts regularly.</b></td>
<td>Maintains a link blog with some collection of useful articles and tools that he/she has collected</td>
<td>Maintains a blog in which personal insights and thoughts on programming are shared</td>
</tr>
</tbody>
</table>
