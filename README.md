# Boo issue archive

The Boo language tracked its issues at `jira.codehaus.org` until Codehaus shut
down in 2015, taking the tracker with it. These pages are recovered from the
Wayback Machine and rendered as markdown, one file per issue.

Each file carries the original fields, description, comments and attachment
list, plus the exact snapshot URLs it was built from. Email addresses appearing
in quoted mailing-list text have had their local part replaced; display names
are kept so contributors stay credited.

Issue numbers here are the original JIRA ids. Filenames are zero padded to four
digits so they sort in numeric order.

## Legend

:white_check_mark: Fixed  
:no_entry_sign: Won't Fix  
:link: Duplicate  
:grey_question: Cannot Reproduce  
:grey_exclamation: Incomplete  
:information_source: Not A Bug  
:large_blue_circle: Open  
:construction: In Progress  
:arrows_counterclockwise: Reopened  
:question: Unknown  

## Issues

| Issue | Status | Title |
|---|---|---|
| [BOO-1](issues/BOO-0001.md) | :no_entry_sign: Won't Fix | Generalize units in the syntax, allow pipeline to define new units |
| [BOO-2](issues/BOO-0002.md) | :white_check_mark: Fixed | static property accessor should be static |
| [BOO-3](issues/BOO-0003.md) | :white_check_mark: Fixed | generator item type is lost |
| [BOO-4](issues/BOO-0004.md) | :white_check_mark: Fixed | array generators |
| [BOO-5](issues/BOO-0005.md) | :large_blue_circle: Open | Document the extensible compilation pipeline |
| [BOO-6](issues/BOO-0006.md) | :white_check_mark: Fixed | MonoDevelop plugin |
| [BOO-7](issues/BOO-0007.md) | :white_check_mark: Fixed | c# style private interface implementations |
| [BOO-8](issues/BOO-0008.md) | :white_check_mark: Fixed | import from clause for weird named assemblies |
| [BOO-9](issues/BOO-0009.md) | :white_check_mark: Fixed | Implement support for final fields (const and literal fields) |
| [BOO-10](issues/BOO-0010.md) | :white_check_mark: Fixed | check visibility for member overrides |
| [BOO-11](issues/BOO-0011.md) | :white_check_mark: Fixed | assert macro |
| [BOO-12](issues/BOO-0012.md) | :white_check_mark: Fixed | change license to MIT/BSD style |
| [BOO-13](issues/BOO-0013.md) | :white_check_mark: Fixed | provide a way to define assembly attributes |
| [BOO-14](issues/BOO-0014.md) | :question: Unknown | *(no title captured)* |
| [BOO-15](issues/BOO-0015.md) | :white_check_mark: Fixed | provide a way to re-raise the current exception |
| [BOO-16](issues/BOO-0016.md) | :large_blue_circle: Open | optimize array unpacking |
| [BOO-17](issues/BOO-0017.md) | :white_check_mark: Fixed | automatic callable type conversion and adaptation |
| [BOO-18](issues/BOO-0018.md) | :white_check_mark: Fixed | boo primer |
| [BOO-19](issues/BOO-0019.md) | :white_check_mark: Fixed | provide a way for user types to participate in duck typing |
| [BOO-20](issues/BOO-0020.md) | :white_check_mark: Fixed | anonymous callable type notation |
| [BOO-21](issues/BOO-0021.md) | :white_check_mark: Fixed | automatic numeric promotion for bool |
| [BOO-22](issues/BOO-0022.md) | :white_check_mark: Fixed | numeric promotion/conversion should happen after unboxing |
| [BOO-24](issues/BOO-0024.md) | :white_check_mark: Fixed | for must call IDisposable.Dispose on enumerator whenever possible |
| [BOO-25](issues/BOO-0025.md) | :white_check_mark: Fixed | hexadecimal integer literals |
| [BOO-27](issues/BOO-0027.md) | :white_check_mark: Fixed | Error checking: constructors can't yield values |
| [BOO-28](issues/BOO-0028.md) | :white_check_mark: Fixed | Error checking: static constructors must be public |
| [BOO-29](issues/BOO-0029.md) | :white_check_mark: Fixed | Error checking: static constructors cannot declare parameters |
| [BOO-30](issues/BOO-0030.md) | :white_check_mark: Fixed | Error checking: can't create instance of interface 'XXX' |
| [BOO-31](issues/BOO-0031.md) | :white_check_mark: Fixed | Error checking: can't create instance of abstract class 'XXX' |
| [BOO-32](issues/BOO-0032.md) | :white_check_mark: Fixed | Error checking: can't create instance of enum 'XXX' |
| [BOO-33](issues/BOO-0033.md) | :white_check_mark: Fixed | Error checking: type 'XXX' already has a definition for a member 'YYY' with the signature 'ZZZ' |
| [BOO-34](issues/BOO-0034.md) | :white_check_mark: Fixed | Error checking: symbols starting with '__', 'get_', 'set_', 'add_' and 'remove_' are reserved by the compiler |
| [BOO-35](issues/BOO-0035.md) | :white_check_mark: Fixed | WARNING: unused local variable |
| [BOO-36](issues/BOO-0036.md) | :large_blue_circle: Open | WARNING: local 'xxx' is used before initialization |
| [BOO-37](issues/BOO-0037.md) | :white_check_mark: Fixed | WARNING: right hand side of 'is' operator is a type reference, are you sure you don't want to use 'isa' instead? |
| [BOO-38](issues/BOO-0038.md) | :white_check_mark: Fixed | WARNING: type 'TTT' does not override abstract member 'XXX.YYY' and will be marked abstract |
| [BOO-39](issues/BOO-0039.md) | :white_check_mark: Fixed | WARNING: type 'TTT' does not implement interface member 'XXX.YYY' and will be marked abstract |
| [BOO-40](issues/BOO-0040.md) | :white_check_mark: Fixed | WARNING: unreachable code detected |
| [BOO-41](issues/BOO-0041.md) | :white_check_mark: Fixed | import external boo modules |
| [BOO-42](issues/BOO-0042.md) | :white_check_mark: Fixed | Move BooC.App.GetPipelineDefinition to Boo.Lang.Compiler.BooCompiler.GetStandardPipelineDefinition |
| [BOO-43](issues/BOO-0043.md) | :large_blue_circle: Open | scope resolution operator :: |
| [BOO-44](issues/BOO-0044.md) | :white_check_mark: Fixed | add pkg-config support to booc and boo nant task |
| [BOO-45](issues/BOO-0045.md) | :white_check_mark: Fixed | Decide on closure/anonymous method syntax |
| [BOO-46](issues/BOO-0046.md) | :white_check_mark: Fixed | compiler does not process standalone member method references correctly |
| [BOO-47](issues/BOO-0047.md) | :white_check_mark: Fixed | numeric promotion from signed to unsigned number types |
| [BOO-48](issues/BOO-0048.md) | :white_check_mark: Fixed | provide a way for a class to expose events |
| [BOO-49](issues/BOO-0049.md) | :white_check_mark: Fixed | Basic "Boo Explorer" functionality ported to gnome |
| [BOO-50](issues/BOO-0050.md) | :white_check_mark: Fixed | booc compile error: BCE0011: An error occurred during the execution of the step Boo.Lang.Compiler.Steps.Emit |
| [BOO-51](issues/BOO-0051.md) | :white_check_mark: Fixed | Add support for classes to implement interfaces with properties |
| [BOO-52](issues/BOO-0052.md) | :white_check_mark: Fixed | Boo Explorer Output Window |
| [BOO-53](issues/BOO-0053.md) | :white_check_mark: Fixed | code completion to booxw |
| [BOO-54](issues/BOO-0054.md) | :white_check_mark: Fixed | Error with += and properties |
| [BOO-55](issues/BOO-0055.md) | :white_check_mark: Fixed | Add support for exposing methods with variable number of arguments |
| [BOO-56](issues/BOO-0056.md) | :white_check_mark: Fixed | Add support for calling methods that support a variable number of arguments |
| [BOO-57](issues/BOO-0057.md) | :white_check_mark: Fixed | Generator methods (yield) |
| [BOO-60](issues/BOO-0060.md) | :white_check_mark: Fixed | UsingMacro improvements |
| [BOO-61](issues/BOO-0061.md) | :white_check_mark: Fixed | Document the project's coding conventions |
| [BOO-62](issues/BOO-0062.md) | :large_blue_circle: Open | monodoc documentation for the Boo and Boo.Lang.Compiler assemblies |
| [BOO-63](issues/BOO-0063.md) | :white_check_mark: Fixed | Read command line resource files. |
| [BOO-64](issues/BOO-0064.md) | :white_check_mark: Fixed | Emit richer debug information (sequence points) |
| [BOO-65](issues/BOO-0065.md) | :white_check_mark: Fixed | getter attribute applied to static field must generate static property |
| [BOO-66](issues/BOO-0066.md) | :white_check_mark: Fixed | property attribute must generate static property when applied to static field |
| [BOO-67](issues/BOO-0067.md) | :white_check_mark: Fixed | closures/anonymous methods |
| [BOO-68](issues/BOO-0068.md) | :white_check_mark: Fixed | asp.net and System.CodeDom integration |
| [BOO-69](issues/BOO-0069.md) | :white_check_mark: Fixed | src attribute for boo task |
| [BOO-70](issues/BOO-0070.md) | :white_check_mark: Fixed | allow callable to be used as an alias to Boo.Lang.ICallable |
| [BOO-71](issues/BOO-0071.md) | :no_entry_sign: Won't Fix | macros don't allow first argument to be an expression starting with a list literal |
| [BOO-72](issues/BOO-0072.md) | :large_blue_circle: Open | pipeline step that generates monodoc documentation files |
| [BOO-73](issues/BOO-0073.md) | :white_check_mark: Fixed | proper support to call methods with ref and out parameters |
| [BOO-74](issues/BOO-0074.md) | :white_check_mark: Fixed | provide a better way to write regression, integration and error checking test cases |
| [BOO-75](issues/BOO-0075.md) | :white_check_mark: Fixed | InvalidOperationException during compilation when using a dynamic assembly as a references |
| [BOO-76](issues/BOO-0076.md) | :white_check_mark: Fixed | Parse error with division |
| [BOO-77](issues/BOO-0077.md) | :white_check_mark: Fixed | Function Overloading/Class Overrideing conflict |
| [BOO-78](issues/BOO-0078.md) | :white_check_mark: Fixed | uint and ulong primitive types |
| [BOO-79](issues/BOO-0079.md) | :no_entry_sign: Won't Fix | use implicit conversion operators |
| [BOO-80](issues/BOO-0080.md) | :white_check_mark: Fixed | implicit conversion from single char string literal to char |
| [BOO-81](issues/BOO-0081.md) | :white_check_mark: Fixed | custom attributes for fields |
| [BOO-82](issues/BOO-0082.md) | :large_blue_circle: Open | XSLT pipeline transformers |
| [BOO-83](issues/BOO-0083.md) | :white_check_mark: Fixed | emitter must honor transient modifier for fields |
| [BOO-84](issues/BOO-0084.md) | :construction: In Progress | Marking strings for i18n |
| [BOO-85](issues/BOO-0085.md) | :white_check_mark: Fixed | Internal compiler error creating char array |
| [BOO-86](issues/BOO-0086.md) | :white_check_mark: Fixed | allow explicit assembly references in boo task |
| [BOO-87](issues/BOO-0087.md) | :large_blue_circle: Open | +, -, +=, -= operators for callable references |
| [BOO-88](issues/BOO-0088.md) | :white_check_mark: Fixed | can't currently create a callable reference with constructor syntax |
| [BOO-89](issues/BOO-0089.md) | :white_check_mark: Fixed | array of nested type crashs the compiler |
| [BOO-90](issues/BOO-0090.md) | :white_check_mark: Fixed | Compiler must look for the DefaultMember attribute in the base class as well |
| [BOO-91](issues/BOO-0091.md) | :white_check_mark: Fixed | precondition for required attribute |
| [BOO-92](issues/BOO-0092.md) | :white_check_mark: Fixed | precondition for property attribute |
| [BOO-93](issues/BOO-0093.md) | :white_check_mark: Fixed | refactor Boo.Lang.Compiler.Steps.GeneratorProcessor to use CodeBuilder |
| [BOO-94](issues/BOO-0094.md) | :white_check_mark: Fixed | true closures |
| [BOO-95](issues/BOO-0095.md) | :white_check_mark: Fixed | custom macro syntax |
| [BOO-96](issues/BOO-0096.md) | :white_check_mark: Fixed | events in interface definitions |
| [BOO-97](issues/BOO-0097.md) | :white_check_mark: Fixed | arrays as hash keys |
| [BOO-98](issues/BOO-0098.md) | :question: Unknown | *(no title captured)* |
| [BOO-99](issues/BOO-0099.md) | :white_check_mark: Fixed | automatic default instance constructor is not generated when the class defines a static constructor |
| [BOO-100](issues/BOO-0100.md) | :white_check_mark: Fixed | "true" generators (as in "true" closures) |
| [BOO-101](issues/BOO-0101.md) | :large_blue_circle: Open | optimize true closures shared variables |
| [BOO-102](issues/BOO-0102.md) | :white_check_mark: Fixed | confuse error message when missing non empty constructor |
| [BOO-103](issues/BOO-0103.md) | :white_check_mark: Fixed | compile fails |
| [BOO-104](issues/BOO-0104.md) | :white_check_mark: Fixed | Internal compiler when calling super constructor |
| [BOO-105](issues/BOO-0105.md) | :white_check_mark: Fixed | Internal compiler error when a event is defined before its callable type |
| [BOO-106](issues/BOO-0106.md) | :white_check_mark: Fixed | preserve array equality even when comparing object references |
| [BOO-107](issues/BOO-0107.md) | :white_check_mark: Fixed | WinForms examples fail |
| [BOO-108](issues/BOO-0108.md) | :white_check_mark: Fixed | checked/unchecked macros to control overflow-checking |
| [BOO-109](issues/BOO-0109.md) | :large_blue_circle: Open | move all type casting processing from EmitAssembly to its own step |
| [BOO-110](issues/BOO-0110.md) | :white_check_mark: Fixed | Duck typing must be enabled by default |
| [BOO-111](issues/BOO-0111.md) | :white_check_mark: Fixed | booc response file |
| [BOO-112](issues/BOO-0112.md) | :white_check_mark: Fixed | python style string format operator (%) |
| [BOO-113](issues/BOO-0113.md) | :white_check_mark: Fixed | reversed iteration |
| [BOO-114](issues/BOO-0114.md) | :large_blue_circle: Open | #line like directive |
| [BOO-115](issues/BOO-0115.md) | :white_check_mark: Fixed | overridable properties |
| [BOO-116](issues/BOO-0116.md) | :white_check_mark: Fixed | provide a way to call arbitrary super class members using super |
| [BOO-117](issues/BOO-0117.md) | :white_check_mark: Fixed | transform (value == null) and (value != null) comparisons in (value is null) and (value is not null) |
| [BOO-118](issues/BOO-0118.md) | :construction: In Progress | full slicing semantics for strings |
| [BOO-119](issues/BOO-0119.md) | :white_check_mark: Fixed | allow event backing fields to be accessed by the event's declaring type |
| [BOO-120](issues/BOO-0120.md) | :white_check_mark: Fixed | abstract properties |
| [BOO-121](issues/BOO-0121.md) | :white_check_mark: Fixed | overloading of indexed properties |
| [BOO-122](issues/BOO-0122.md) | :white_check_mark: Fixed | static methods of precompiled classes are not visible in derived types |
| [BOO-123](issues/BOO-0123.md) | :white_check_mark: Fixed | Internal compiler error |
| [BOO-124](issues/BOO-0124.md) | :white_check_mark: Fixed | Internal compiler error related to interface definition |
| [BOO-125](issues/BOO-0125.md) | :white_check_mark: Fixed | ternary expression |
| [BOO-126](issues/BOO-0126.md) | :white_check_mark: Fixed | optimize array creation |
| [BOO-127](issues/BOO-0127.md) | :white_check_mark: Fixed | raise should only accept string and exception instances |
| [BOO-128](issues/BOO-0128.md) | :question: Unknown | *(no title captured)* |
| [BOO-129](issues/BOO-0129.md) | :white_check_mark: Fixed | internal compiler error for enum nested in class |
| [BOO-130](issues/BOO-0130.md) | :white_check_mark: Fixed | use relative file paths instead of absolute file paths in compiler output |
| [BOO-131](issues/BOO-0131.md) | :white_check_mark: Fixed | Error checking: Cannot extend final class |
| [BOO-132](issues/BOO-0132.md) | :white_check_mark: Fixed | Error checking: Cannot extend System.ValueType |
| [BOO-133](issues/BOO-0133.md) | :white_check_mark: Fixed | print macro |
| [BOO-134](issues/BOO-0134.md) | :white_check_mark: Fixed | else if |
| [BOO-135](issues/BOO-0135.md) | :no_entry_sign: Won't Fix | given statement for integer values |
| [BOO-136](issues/BOO-0136.md) | :no_entry_sign: Won't Fix | generic given statement |
| [BOO-137](issues/BOO-0137.md) | :white_check_mark: Fixed | optimize for item in array construct |
| [BOO-138](issues/BOO-0138.md) | :white_check_mark: Fixed | Cannot add handler to static event |
| [BOO-139](issues/BOO-0139.md) | :white_check_mark: Fixed | boo interactive interpreter |
| [BOO-140](issues/BOO-0140.md) | :white_check_mark: Fixed | interactive interpreter window for booxw |
| [BOO-141](issues/BOO-0141.md) | :white_check_mark: Fixed | OPTIMIZATION: cache external type information in Steps.InitializeNameResolutionService |
| [BOO-142](issues/BOO-0142.md) | :white_check_mark: Fixed | booish fails to process unpacking statements |
| [BOO-143](issues/BOO-0143.md) | :white_check_mark: Fixed | bitwise and operator: & |
| [BOO-144](issues/BOO-0144.md) | :large_blue_circle: Open | Error Checking: Module classes can't have instance members |
| [BOO-145](issues/BOO-0145.md) | :white_check_mark: Fixed | System.NullReferenceException in assignments to fields of value types |
| [BOO-146](issues/BOO-0146.md) | :white_check_mark: Fixed | operator + for arrays |
| [BOO-147](issues/BOO-0147.md) | :white_check_mark: Fixed | booish fails to process assignments with a right hand side method.BeginInvoke() |
| [BOO-148](issues/BOO-0148.md) | :white_check_mark: Fixed | booish: InvalidCastException when evaluation method.EndInvoke |
| [BOO-149](issues/BOO-0149.md) | :white_check_mark: Fixed | field access through duck typed reference |
| [BOO-150](issues/BOO-0150.md) | :white_check_mark: Fixed | parser fails to recognize closures inside string interpolation expressions |
| [BOO-151](issues/BOO-0151.md) | :white_check_mark: Fixed | Invalid cast blows up booi, booc, boox, etc |
| [BOO-152](issues/BOO-0152.md) | :white_check_mark: Fixed | Modify trace pipeline to time called routines |
| [BOO-153](issues/BOO-0153.md) | :white_check_mark: Fixed | call one contructor from another |
| [BOO-154](issues/BOO-0154.md) | :white_check_mark: Fixed | value types |
| [BOO-155](issues/BOO-0155.md) | :white_check_mark: Fixed | import <namespace> from <assembly> does not take referenced assemblies into account |
| [BOO-156](issues/BOO-0156.md) | :white_check_mark: Fixed | ulong array bug |
| [BOO-157](issues/BOO-0157.md) | :no_entry_sign: Won't Fix | Print macro bug |
| [BOO-158](issues/BOO-0158.md) | :large_blue_circle: Open | [Field] attribute auto-assigns constructor parameters onto fields |
| [BOO-159](issues/BOO-0159.md) | :white_check_mark: Fixed | Transient methods and abstract fields |
| [BOO-160](issues/BOO-0160.md) | :white_check_mark: Fixed | boox prints the wrong output for ast-to-string.boo |
| [BOO-161](issues/BOO-0161.md) | :large_blue_circle: Open | Static fields in methods |
| [BOO-162](issues/BOO-0162.md) | :grey_question: Cannot Reproduce | static properties |
| [BOO-164](issues/BOO-0164.md) | :no_entry_sign: Won't Fix | Illegal private member access ignores try block |
| [BOO-165](issues/BOO-0165.md) | :white_check_mark: Fixed | static events |
| [BOO-166](issues/BOO-0166.md) | :white_check_mark: Fixed | Enabled duck typing for static members |
| [BOO-167](issues/BOO-0167.md) | :white_check_mark: Fixed | boo CodeDomProvider |
| [BOO-168](issues/BOO-0168.md) | :large_blue_circle: Open | WARNING: Conversion from 'foo' to 'bar' can cause loss of information |
| [BOO-170](issues/BOO-0170.md) | :large_blue_circle: Open | Timer macro |
| [BOO-171](issues/BOO-0171.md) | :white_check_mark: Fixed | Compile error for -= event handler statment |
| [BOO-172](issues/BOO-0172.md) | :white_check_mark: Fixed | Improved the error message when property precondition fails |
| [BOO-173](issues/BOO-0173.md) | :white_check_mark: Fixed | Multi-dimensional arrays. |
| [BOO-174](issues/BOO-0174.md) | :white_check_mark: Fixed | Assignment operator bug |
| [BOO-175](issues/BOO-0175.md) | :white_check_mark: Fixed | Improved the error message when required condition fails |
| [BOO-176](issues/BOO-0176.md) | :white_check_mark: Fixed | abstract class that contains another class |
| [BOO-177](issues/BOO-0177.md) | :white_check_mark: Fixed | -resource compiler option |
| [BOO-178](issues/BOO-0178.md) | :white_check_mark: Fixed | Calling ToString on enum raises ExecutionEngineException |
| [BOO-179](issues/BOO-0179.md) | :white_check_mark: Fixed | Broken property overrides |
| [BOO-180](issues/BOO-0180.md) | :white_check_mark: Fixed | value type arrays |
| [BOO-181](issues/BOO-0181.md) | :white_check_mark: Fixed | struct keyword for simpler value type declaration |
| [BOO-182](issues/BOO-0182.md) | :white_check_mark: Fixed | #develop addin |
| [BOO-183](issues/BOO-0183.md) | :white_check_mark: Fixed | #develop interactive interpreter pad/view |
| [BOO-184](issues/BOO-0184.md) | :white_check_mark: Fixed | #develop class browser |
| [BOO-185](issues/BOO-0185.md) | :no_entry_sign: Won't Fix | command line handling with Mono.GetOptions |
| [BOO-186](issues/BOO-0186.md) | :white_check_mark: Fixed | #develop code completion |
| [BOO-187](issues/BOO-0187.md) | :white_check_mark: Fixed | Booish.gui fails to redirect standard output to a visible form. |
| [BOO-188](issues/BOO-0188.md) | :white_check_mark: Fixed | Compiler allows override when no method with that signature |
| [BOO-189](issues/BOO-0189.md) | :white_check_mark: Fixed | NullReferenceException when setting value type property |
| [BOO-190](issues/BOO-0190.md) | :question: Unknown | *(no title captured)* |
| [BOO-191](issues/BOO-0191.md) | :white_check_mark: Fixed | #develop use dll instead of booc to compile |
| [BOO-192](issues/BOO-0192.md) | :white_check_mark: Fixed | duck typing - indexed property access |
| [BOO-193](issues/BOO-0193.md) | :white_check_mark: Fixed | duck typing - operators |
| [BOO-195](issues/BOO-0195.md) | :white_check_mark: Fixed | Struct keyword produces compiler error |
| [BOO-196](issues/BOO-0196.md) | :white_check_mark: Fixed | Can't use value type in another class or struct |
| [BOO-198](issues/BOO-0198.md) | :no_entry_sign: Won't Fix | BooXW doesn't play nice with mono |
| [BOO-199](issues/BOO-0199.md) | :white_check_mark: Fixed | xor ^= and ^ binary operator |
| [BOO-200](issues/BOO-0200.md) | :white_check_mark: Fixed | Expressions involving unsigneds not promoting correctly |
| [BOO-201](issues/BOO-0201.md) | :white_check_mark: Fixed | print AST visitor |
| [BOO-202](issues/BOO-0202.md) | :white_check_mark: Fixed | Warnings result in failure to launch application. |
| [BOO-203](issues/BOO-0203.md) | :white_check_mark: Fixed | "Duckiness" not propagated in chained operation |
| [BOO-204](issues/BOO-0204.md) | :white_check_mark: Fixed | Sped up duck operators 6 times |
| [BOO-205](issues/BOO-0205.md) | :information_source: Not A Bug | First static method 10 times slower to call |
| [BOO-206](issues/BOO-0206.md) | :large_blue_circle: Open | Overload assignment operator, and implicit conversion |
| [BOO-207](issues/BOO-0207.md) | :question: Unknown | *(no title captured)* |
| [BOO-209](issues/BOO-0209.md) | :question: Unknown | *(no title captured)* |
| [BOO-210](issues/BOO-0210.md) | :white_check_mark: Fixed | Returning self when self is a struct causes fatal execution engine error in booi |
| [BOO-211](issues/BOO-0211.md) | :white_check_mark: Fixed | Improve booish.gui's code completion. |
| [BOO-212](issues/BOO-0212.md) | :white_check_mark: Fixed | Strong name for Boo.dll, Boo.Lang.Compiler.dll and Boo.AntlrParser.dll |
| [BOO-213](issues/BOO-0213.md) | :white_check_mark: Fixed | Support for creating strong named assemblies |
| [BOO-214](issues/BOO-0214.md) | :white_check_mark: Fixed | booish.gui - users can backspace over ">>>" and "..." prompts. |
| [BOO-215](issues/BOO-0215.md) | :white_check_mark: Fixed | Implement SharpDevelop abstract parser layer |
| [BOO-216](issues/BOO-0216.md) | :white_check_mark: Fixed | Made macros consistently inherit AbstractAstMacro |
| [BOO-217](issues/BOO-0217.md) | :white_check_mark: Fixed | Add unary overloadable operators |
| [BOO-218](issues/BOO-0218.md) | :white_check_mark: Fixed | duck typing - unary operators |
| [BOO-219](issues/BOO-0219.md) | :white_check_mark: Fixed | BooAmbience |
| [BOO-220](issues/BOO-0220.md) | :white_check_mark: Fixed | numeric constants in attributes are not supported |
| [BOO-221](issues/BOO-0221.md) | :large_blue_circle: Open | booish.gui.exe doesn't handle infinite loops gracefully |
| [BOO-222](issues/BOO-0222.md) | :white_check_mark: Fixed | Implemented IQuackFu operators |
| [BOO-223](issues/BOO-0223.md) | :large_blue_circle: Open | Improve Operator Override (and General Comparison) |
| [BOO-224](issues/BOO-0224.md) | :white_check_mark: Fixed | allow for partial classes |
| [BOO-225](issues/BOO-0225.md) | :white_check_mark: Fixed | italian resource file |
| [BOO-226](issues/BOO-0226.md) | :white_check_mark: Fixed | ValueType.ToString() aborts runtime |
| [BOO-227](issues/BOO-0227.md) | :white_check_mark: Fixed | Overridden Equals (==) not commutative |
| [BOO-228](issues/BOO-0228.md) | :question: Unknown | *(no title captured)* |
| [BOO-229](issues/BOO-0229.md) | :white_check_mark: Fixed | And / Or duck-typing bugs |
| [BOO-230](issues/BOO-0230.md) | :white_check_mark: Fixed | Explicit conversions |
| [BOO-231](issues/BOO-0231.md) | :white_check_mark: Fixed | Bug in "not" operator |
| [BOO-232](issues/BOO-0232.md) | :white_check_mark: Fixed | a = array(string,(1,2,3)) aborts compiler |
| [BOO-233](issues/BOO-0233.md) | :white_check_mark: Fixed | Added decimal type and unary negation operator overloading |
| [BOO-234](issues/BOO-0234.md) | :white_check_mark: Fixed | new map overload |
| [BOO-235](issues/BOO-0235.md) | :large_blue_circle: Open | Code Completion fails when using "import <namespace>" |
| [BOO-236](issues/BOO-0236.md) | :white_check_mark: Fixed | Support for inferred return types. |
| [BOO-237](issues/BOO-0237.md) | :white_check_mark: Fixed | allow extraneous comma is arrays and lists |
| [BOO-238](issues/BOO-0238.md) | :white_check_mark: Fixed | Code Completion not very "accurate." |
| [BOO-240](issues/BOO-0240.md) | :white_check_mark: Fixed | Code completion for arrays does not work in all cases. |
| [BOO-241](issues/BOO-0241.md) | :white_check_mark: Fixed | Nested classes not working |
| [BOO-242](issues/BOO-0242.md) | :white_check_mark: Fixed | Code Completion fails when using fully qualified classes. |
| [BOO-243](issues/BOO-0243.md) | :white_check_mark: Fixed | BooBinding not releasing assembly dependencies in projects. |
| [BOO-244](issues/BOO-0244.md) | :white_check_mark: Fixed | print macro ignores if conditionals. |
| [BOO-245](issues/BOO-0245.md) | :large_blue_circle: Open | Duck typing do not survive compilation |
| [BOO-246](issues/BOO-0246.md) | :white_check_mark: Fixed | Implicit duck typing option |
| [BOO-247](issues/BOO-0247.md) | :no_entry_sign: Won't Fix | assert still active in release build (debug off) |
| [BOO-248](issues/BOO-0248.md) | :white_check_mark: Fixed | Bug in decimals w/duck typing |
| [BOO-249](issues/BOO-0249.md) | :white_check_mark: Fixed | A new binary release. |
| [BOO-250](issues/BOO-0250.md) | :arrows_counterclockwise: Reopened | overloaded functions cannot be "first class functions" |
| [BOO-251](issues/BOO-0251.md) | :white_check_mark: Fixed | Local variables not falling out of scope properly. |
| [BOO-252](issues/BOO-0252.md) | :white_check_mark: Fixed | Code Completion in abstract classes does not function. |
| [BOO-253](issues/BOO-0253.md) | :white_check_mark: Fixed | Substraction operator overloading called op_subtraction instead of op_substraction |
| [BOO-254](issues/BOO-0254.md) | :white_check_mark: Fixed | Boo's builtin regular expresses + code completion = error. |
| [BOO-255](issues/BOO-0255.md) | :white_check_mark: Fixed | Allow outside scopes to be used by boo interpreter |
| [BOO-256](issues/BOO-0256.md) | :white_check_mark: Fixed | explict conversions from char to integers and integers to char |
| [BOO-257](issues/BOO-0257.md) | :white_check_mark: Fixed | booc task should check for updated targets |
| [BOO-258](issues/BOO-0258.md) | :white_check_mark: Fixed | check variable access and privileges at compile time |
| [BOO-259](issues/BOO-0259.md) | :question: Unknown | *(no title captured)* |
| [BOO-260](issues/BOO-0260.md) | :white_check_mark: Fixed | incorrect check of void return type |
| [BOO-261](issues/BOO-0261.md) | :white_check_mark: Fixed | compiler error on passing a callable with incorrect nbr of params |
| [BOO-262](issues/BOO-0262.md) | :question: Unknown | *(no title captured)* |
| [BOO-263](issues/BOO-0263.md) | :white_check_mark: Fixed | Wildcards not admited in [assembly: AssemblyVersion("1.0.*")] |
| [BOO-264](issues/BOO-0264.md) | :white_check_mark: Fixed | by ref parameters |
| [BOO-265](issues/BOO-0265.md) | :white_check_mark: Fixed | Named argument support for IQuackFu |
| [BOO-266](issues/BOO-0266.md) | :large_blue_circle: Open | Honor CLSCompliantAttribute or implement /cls switch. |
| [BOO-267](issues/BOO-0267.md) | :no_entry_sign: Won't Fix | simple Makefile-based build |
| [BOO-268](issues/BOO-0268.md) | :white_check_mark: Fixed | "Setup Error" |
| [BOO-269](issues/BOO-0269.md) | :white_check_mark: Fixed | raw array indexing |
| [BOO-270](issues/BOO-0270.md) | :white_check_mark: Fixed | error with bitwiseor in attribute constructor |
| [BOO-271](issues/BOO-0271.md) | :white_check_mark: Fixed | AttributeUsage ignored |
| [BOO-272](issues/BOO-0272.md) | :large_blue_circle: Open | interpreter bug with byref params |
| [BOO-274](issues/BOO-0274.md) | :large_blue_circle: Open | -win32icon option |
| [BOO-275](issues/BOO-0275.md) | :white_check_mark: Fixed | -nostdlib option |
| [BOO-276](issues/BOO-0276.md) | :white_check_mark: Fixed | Add left (<<) and right (>>) shift operator to Boo |
| [BOO-277](issues/BOO-0277.md) | :white_check_mark: Fixed | Indexed properties with more than1 index |
| [BOO-278](issues/BOO-0278.md) | :white_check_mark: Fixed | "not" operator precedence |
| [BOO-279](issues/BOO-0279.md) | :large_blue_circle: Open | Ant build-file for boox requires SharpDevelop directory |
| [BOO-280](issues/BOO-0280.md) | :white_check_mark: Fixed | Explicit interface implementation |
| [BOO-281](issues/BOO-0281.md) | :white_check_mark: Fixed | Calling ToString not possible on integer values in multidimensional arrays |
| [BOO-282](issues/BOO-0282.md) | :large_blue_circle: Open | optimize multidimensional array handling |
| [BOO-283](issues/BOO-0283.md) | :large_blue_circle: Open | textual IL emitter step |
| [BOO-284](issues/BOO-0284.md) | :no_entry_sign: Won't Fix | Boox and GTK# not playing nicely. |
| [BOO-285](issues/BOO-0285.md) | :white_check_mark: Fixed | #develop crashes on untyped [property()] |
| [BOO-286](issues/BOO-0286.md) | :white_check_mark: Fixed | SVN 1486 (GAC-Friendly way of loading assembly) breaks BooBinding. |
| [BOO-287](issues/BOO-0287.md) | :white_check_mark: Fixed | Properties with same name as property type cause compiler error |
| [BOO-288](issues/BOO-0288.md) | :no_entry_sign: Won't Fix | Jagged array declaration syntax should be fixed. |
| [BOO-289](issues/BOO-0289.md) | :question: Unknown | *(no title captured)* |
| [BOO-291](issues/BOO-0291.md) | :white_check_mark: Fixed | BooCodeGenerator generates illegal code for arrays |
| [BOO-292](issues/BOO-0292.md) | :white_check_mark: Fixed | treat any subclass of IQuackFu as a duck when Ducky is set |
| [BOO-293](issues/BOO-0293.md) | :large_blue_circle: Open | The compiler throws an exception when a resource file contains a ImageListStreamer |
| [BOO-294](issues/BOO-0294.md) | :no_entry_sign: Won't Fix | MD Matrix with initalization builtin. |
| [BOO-295](issues/BOO-0295.md) | :white_check_mark: Fixed | allow \a and other special characters |
| [BOO-296](issues/BOO-0296.md) | :white_check_mark: Fixed | Add Set class to Boo.Lang |
| [BOO-297](issues/BOO-0297.md) | :white_check_mark: Fixed | Enum values can't be negative |
| [BOO-298](issues/BOO-0298.md) | :white_check_mark: Fixed | len overload for multidimensional arrays |
| [BOO-299](issues/BOO-0299.md) | :white_check_mark: Fixed | treat duck as callable |
| [BOO-300](issues/BOO-0300.md) | :white_check_mark: Fixed | #region folding |
| [BOO-301](issues/BOO-0301.md) | :white_check_mark: Fixed | Infinite loop when breaking in a while loop after a nested for loop |
| [BOO-302](issues/BOO-0302.md) | :white_check_mark: Fixed | EvalFile in interpreter |
| [BOO-303](issues/BOO-0303.md) | :white_check_mark: Fixed | Improve interactive interpreter welcome message. |
| [BOO-305](issues/BOO-0305.md) | :large_blue_circle: Open | Add slice assignment / swap array members |
| [BOO-306](issues/BOO-0306.md) | :large_blue_circle: Open | "Send --> To Interactive Interpreter Pad" |
| [BOO-307](issues/BOO-0307.md) | :arrows_counterclockwise: Reopened | Preprocessor directives |
| [BOO-308](issues/BOO-0308.md) | :white_check_mark: Fixed | duck typing - assignment to indexed property |
| [BOO-309](issues/BOO-0309.md) | :large_blue_circle: Open | booish is missing contextual menu |
| [BOO-310](issues/BOO-0310.md) | :white_check_mark: Fixed | multi generator expression |
| [BOO-311](issues/BOO-0311.md) | :no_entry_sign: Won't Fix | Extend "for" generator syntax to the "for" statement |
| [BOO-312](issues/BOO-0312.md) | :white_check_mark: Fixed | "cat" built-in. |
| [BOO-313](issues/BOO-0313.md) | :arrows_counterclockwise: Reopened | changing struct values accessed with properties |
| [BOO-314](issues/BOO-0314.md) | :white_check_mark: Fixed | Overeager member lookup in classes |
| [BOO-315](issues/BOO-0315.md) | :white_check_mark: Fixed | SingletonAttribute |
| [BOO-317](issues/BOO-0317.md) | :large_blue_circle: Open | Boo.Lang.Useful.Attributes.AsyncMethodAttribute |
| [BOO-318](issues/BOO-0318.md) | :large_blue_circle: Open | Boo.Lang.Useful.Macros.FireAndForgetMacro |
| [BOO-319](issues/BOO-0319.md) | :large_blue_circle: Open | Boo.Lang.Useful.Attributes.DisposableAttribute |
| [BOO-320](issues/BOO-0320.md) | :link: Duplicate | Memoize attribute in Boo.Lang.Useful.Attributes |
| [BOO-321](issues/BOO-0321.md) | :white_check_mark: Fixed | CodedomVisitor.boo does not implement OnCharLiteralExpression |
| [BOO-322](issues/BOO-0322.md) | :no_entry_sign: Won't Fix | Attack of the missing members in code completion! |
| [BOO-323](issues/BOO-0323.md) | :white_check_mark: Fixed | Add "help" to booc. |
| [BOO-326](issues/BOO-0326.md) | :white_check_mark: Fixed | Overloaded ?== and != are not called |
| [BOO-327](issues/BOO-0327.md) | :grey_question: Cannot Reproduce | Type inference error when calling outside module class |
| [BOO-329](issues/BOO-0329.md) | :white_check_mark: Fixed | Improved namespace code completion. |
| [BOO-330](issues/BOO-0330.md) | :white_check_mark: Fixed | Codecompletion does not include events. |
| [BOO-331](issues/BOO-0331.md) | :white_check_mark: Fixed | use implicit bool conversions when available |
| [BOO-332](issues/BOO-0332.md) | :large_blue_circle: Open | automatically create temporary variables for ref/out arguments |
| [BOO-333](issues/BOO-0333.md) | :white_check_mark: Fixed | Events can be directly raised outside of defining assembly. |
| [BOO-334](issues/BOO-0334.md) | :white_check_mark: Fixed | for and unpack statements should work with IEnumerator |
| [BOO-335](issues/BOO-0335.md) | :white_check_mark: Fixed | for and unpack statements should work with any type that exposes a compatible GetEnumerator method |
| [BOO-336](issues/BOO-0336.md) | :white_check_mark: Fixed | Boo.Lang.Hash does not override Clone. |
| [BOO-337](issues/BOO-0337.md) | :white_check_mark: Fixed | Allow "in" keyword to work with IEnumerable types. |
| [BOO-338](issues/BOO-0338.md) | :white_check_mark: Fixed | System.InvalidProgramException with try/ensure. |
| [BOO-340](issues/BOO-0340.md) | :white_check_mark: Fixed | Error with processing of explicit interface members |
| [BOO-342](issues/BOO-0342.md) | :question: Unknown | *(no title captured)* |
| [BOO-343](issues/BOO-0343.md) | :no_entry_sign: Won't Fix | Reduce() and other functional additions |
| [BOO-344](issues/BOO-0344.md) | :white_check_mark: Fixed | MSBuild Task for Boo Compiler |
| [BOO-345](issues/BOO-0345.md) | :question: Unknown | *(no title captured)* |
| [BOO-346](issues/BOO-0346.md) | :white_check_mark: Fixed | Addin does not reference Boo.Lang.Useful by default. |
| [BOO-347](issues/BOO-0347.md) | :white_check_mark: Fixed | BooBinding does not detect methods generated by AST Attributes. |
| [BOO-348](issues/BOO-0348.md) | :white_check_mark: Fixed | boo.rsp relies on assemblies not included in mono-core |
| [BOO-349](issues/BOO-0349.md) | :white_check_mark: Fixed | Uninstall from Windows GAC |
| [BOO-350](issues/BOO-0350.md) | :white_check_mark: Fixed | allow assemblies to be generated only in disk |
| [BOO-351](issues/BOO-0351.md) | :large_blue_circle: Open | Better handling of cast() with duck typing? |
| [BOO-352](issues/BOO-0352.md) | :white_check_mark: Fixed | Boo.Lang.Useful.Collection.Cache |
| [BOO-353](issues/BOO-0353.md) | :white_check_mark: Fixed | BooCodeGenerator generates illegal code for non-inheriting classes |
| [BOO-354](issues/BOO-0354.md) | :large_blue_circle: Open | Boo.Lang.Useful.Attributes.CacheAttribute |
| [BOO-355](issues/BOO-0355.md) | :white_check_mark: Fixed | Reference Boo.Lang.Useful by default. |
| [BOO-356](issues/BOO-0356.md) | :white_check_mark: Fixed | Error BCE0011 "Cannot cast from source type to destination type." when assigning to callable |
| [BOO-357](issues/BOO-0357.md) | :white_check_mark: Fixed | Function does not get overriden |
| [BOO-359](issues/BOO-0359.md) | :large_blue_circle: Open | using does not accept value types |
| [BOO-360](issues/BOO-0360.md) | :white_check_mark: Fixed | cannot put doc string on enum |
| [BOO-361](issues/BOO-0361.md) | :white_check_mark: Fixed | assert can be confused by comment with some assertion types |
| [BOO-362](issues/BOO-0362.md) | :no_entry_sign: Won't Fix | Boo does not adhere to op_Implicit. |
| [BOO-363](issues/BOO-0363.md) | :white_check_mark: Fixed | Type inference does not take inherited abstract members into account |
| [BOO-364](issues/BOO-0364.md) | :white_check_mark: Fixed | post increment and post decrement operators |
| [BOO-365](issues/BOO-0365.md) | :white_check_mark: Fixed | allow yield to be used without an expression |
| [BOO-366](issues/BOO-0366.md) | :white_check_mark: Fixed | Remove one level of indirection from generators and allow generator methods to use IEnumerator as the return type |
| [BOO-367](issues/BOO-0367.md) | :white_check_mark: Fixed | boo compiler loops forever when a closure is passed as argument of a field initializer |
| [BOO-368](issues/BOO-0368.md) | :white_check_mark: Fixed | Cannot pass a close as argument of a field initializer with the def(): ... syntax |
| [BOO-369](issues/BOO-0369.md) | :white_check_mark: Fixed | compiler internal error when a field has an initialiser taking a closure as argument |
| [BOO-370](issues/BOO-0370.md) | :white_check_mark: Fixed | Initialisers aren't emited in order all the time |
| [BOO-372](issues/BOO-0372.md) | :white_check_mark: Fixed | Internal Compiler Error when resolving method overloads which contain newslot methods with byref arguments |
| [BOO-373](issues/BOO-0373.md) | :white_check_mark: Fixed | And the unary complement operator (~) |
| [BOO-374](issues/BOO-0374.md) | :white_check_mark: Fixed | Error checking: check signature of implemented abstract members |
| [BOO-375](issues/BOO-0375.md) | :white_check_mark: Fixed | char() should accept int literal as argument |
| [BOO-376](issues/BOO-0376.md) | :white_check_mark: Fixed | properly detect and report type inference cycles |
| [BOO-377](issues/BOO-0377.md) | :white_check_mark: Fixed | WARNING: assingment inside condition |
| [BOO-378](issues/BOO-0378.md) | :white_check_mark: Fixed | command line option to booi: -w (print warnings) |
| [BOO-379](issues/BOO-0379.md) | :white_check_mark: Fixed | as operator precedence is too low |
| [BOO-380](issues/BOO-0380.md) | :white_check_mark: Fixed | Namespace aliases handled incorrectly during code completion. |
| [BOO-381](issues/BOO-0381.md) | :white_check_mark: Fixed | Enhancements to property and required attributes |
| [BOO-382](issues/BOO-0382.md) | :white_check_mark: Fixed | have booc check current directory for referenced dlls |
| [BOO-383](issues/BOO-0383.md) | :white_check_mark: Fixed | The parser should check when the keyword 'super' is used in an invalid context. |
| [BOO-384](issues/BOO-0384.md) | :white_check_mark: Fixed | Boo should catch invalid Main signatures. |
| [BOO-385](issues/BOO-0385.md) | :large_blue_circle: Open | callables which take a variable number of arguments |
| [BOO-386](issues/BOO-0386.md) | :large_blue_circle: Open | Check for an existing constructor for classes with [Module] |
| [BOO-387](issues/BOO-0387.md) | :large_blue_circle: Open | Private properties crash .NET Reflector |
| [BOO-388](issues/BOO-0388.md) | :large_blue_circle: Open | Boo.Lang.Useful.Attributes.HandlesAttribute |
| [BOO-389](issues/BOO-0389.md) | :white_check_mark: Fixed | Invalid attribute declaration causes a NullReferenceException in Booc |
| [BOO-390](issues/BOO-0390.md) | :white_check_mark: Fixed | The compiler is confused when an attribute declaration match a non-attribute |
| [BOO-391](issues/BOO-0391.md) | :large_blue_circle: Open | Modify [required] attribute to allow for post-condition checks. |
| [BOO-392](issues/BOO-0392.md) | :grey_question: Cannot Reproduce | An assert fails during compile |
| [BOO-393](issues/BOO-0393.md) | :white_check_mark: Fixed | Get full method signature when not implementing the full contract of an abstract class / interface |
| [BOO-394](issues/BOO-0394.md) | :white_check_mark: Fixed | Correct Attribute.ToString() |
| [BOO-396](issues/BOO-0396.md) | :white_check_mark: Fixed | Closures can't use the fantastical variable input magic. |
| [BOO-397](issues/BOO-0397.md) | :white_check_mark: Fixed | Two fields, same name, results in compiler error rather than friendly error message. |
| [BOO-398](issues/BOO-0398.md) | :white_check_mark: Fixed | Brace-based closures do not work with varargs syntax. |
| [BOO-399](issues/BOO-0399.md) | :large_blue_circle: Open | The [Module] attribute should automagically make all members static. |
| [BOO-400](issues/BOO-0400.md) | :white_check_mark: Fixed | Boo is emitting bad IL when dealing with PInvokes. |
| [BOO-401](issues/BOO-0401.md) | :no_entry_sign: Won't Fix | Boo.Lang.CodeDOM improvements |
| [BOO-402](issues/BOO-0402.md) | :white_check_mark: Fixed | Add information to duplicate name on types |
| [BOO-403](issues/BOO-0403.md) | :white_check_mark: Fixed | named file resources |
| [BOO-404](issues/BOO-0404.md) | :white_check_mark: Fixed | custom parameter attributes |
| [BOO-405](issues/BOO-0405.md) | :large_blue_circle: Open | Confusing error message for missing identifier in string interpolation |
| [BOO-406](issues/BOO-0406.md) | :white_check_mark: Fixed | explode operator |
| [BOO-407](issues/BOO-0407.md) | :white_check_mark: Fixed | Calling params inside of a closure is broken. |
| [BOO-408](issues/BOO-0408.md) | :white_check_mark: Fixed | Explode operator not exploding when using overloaded methods |
| [BOO-409](issues/BOO-0409.md) | :white_check_mark: Fixed | Using as cast with callables |
| [BOO-410](issues/BOO-0410.md) | :white_check_mark: Fixed | Bad error message with structs that have partially implement interfaces. |
| [BOO-411](issues/BOO-0411.md) | :white_check_mark: Fixed | type inference for operator methods is done too late |
| [BOO-412](issues/BOO-0412.md) | :white_check_mark: Fixed | Keywords in a namespace? Oops! |
| [BOO-413](issues/BOO-0413.md) | :question: Unknown | *(no title captured)* |
| [BOO-414](issues/BOO-0414.md) | :large_blue_circle: Open | chained comparisons |
| [BOO-415](issues/BOO-0415.md) | :white_check_mark: Fixed | Type member macros |
| [BOO-416](issues/BOO-0416.md) | :large_blue_circle: Open | Sensible error message for mistakes from C# |
| [BOO-417](issues/BOO-0417.md) | :white_check_mark: Fixed | Casting self as duck removes visibility level. ;( |
| [BOO-418](issues/BOO-0418.md) | :no_entry_sign: Won't Fix | Boo silently return null for method with return types without return statements |
| [BOO-419](issues/BOO-0419.md) | :question: Unknown | *(no title captured)* |
| [BOO-420](issues/BOO-0420.md) | :white_check_mark: Fixed | cannot cast from boxed char to int and back |
| [BOO-421](issues/BOO-0421.md) | :question: Unknown | *(no title captured)* |
| [BOO-422](issues/BOO-0422.md) | :white_check_mark: Fixed | Boo.Lang.Codedom in Boo |
| [BOO-423](issues/BOO-0423.md) | :white_check_mark: Fixed | Timespan literals won't work with numbers starting with decimal point |
| [BOO-424](issues/BOO-0424.md) | :white_check_mark: Fixed | Exponential notation |
| [BOO-425](issues/BOO-0425.md) | :white_check_mark: Fixed | Digit grouping for readability |
| [BOO-426](issues/BOO-0426.md) | :white_check_mark: Fixed | float literals |
| [BOO-428](issues/BOO-0428.md) | :white_check_mark: Fixed | Check negative number literals at compile time |
| [BOO-429](issues/BOO-0429.md) | :large_blue_circle: Open | Complex number literals and builtin type |
| [BOO-430](issues/BOO-0430.md) | :large_blue_circle: Open | Delegate Attribute |
| [BOO-431](issues/BOO-0431.md) | :large_blue_circle: Open | Documentation AST Nodes |
| [BOO-432](issues/BOO-0432.md) | :large_blue_circle: Open | [IDE Integration] Arbitrary retrieval of AST nodes |
| [BOO-433](issues/BOO-0433.md) | :white_check_mark: Fixed | Can't build to .net 1.1 using Boo.NAnt if .Net framework 2.0 is installed |
| [BOO-434](issues/BOO-0434.md) | :white_check_mark: Fixed | ResourceFu (better than Ayende's!) |
| [BOO-435](issues/BOO-0435.md) | :large_blue_circle: Open | decimal literal |
| [BOO-436](issues/BOO-0436.md) | :white_check_mark: Fixed | Smarter Boo integration (Macros, Attributes, Modules, and Imported Classes) |
| [BOO-437](issues/BOO-0437.md) | :white_check_mark: Fixed | allow curly braces in regex literals |
| [BOO-438](issues/BOO-0438.md) | :large_blue_circle: Open | C# and VB parser |
| [BOO-439](issues/BOO-0439.md) | :white_check_mark: Fixed | Ast attributes are not applied to index properties |
| [BOO-440](issues/BOO-0440.md) | :white_check_mark: Fixed | compiler doesn't have override & overload of indexed properties |
| [BOO-441](issues/BOO-0441.md) | :white_check_mark: Fixed | array[index] += 1 does not compile |
| [BOO-442](issues/BOO-0442.md) | :white_check_mark: Fixed | static constructor related bugs (3 for 1 sale!) |
| [BOO-443](issues/BOO-0443.md) | :white_check_mark: Fixed | Parameterless initialization of structs |
| [BOO-444](issues/BOO-0444.md) | :large_blue_circle: Open | Lazy value type initialization not shown in ToCodeString() |
| [BOO-445](issues/BOO-0445.md) | :white_check_mark: Fixed | Inplace binary operators do not work with ducks |
| [BOO-446](issues/BOO-0446.md) | :large_blue_circle: Open | Apply explode operator to non varargs parameters |
| [BOO-447](issues/BOO-0447.md) | :white_check_mark: Fixed | Addin for SharpDevelop 2.0 |
| [BOO-448](issues/BOO-0448.md) | :large_blue_circle: Open | Generics |
| [BOO-449](issues/BOO-0449.md) | :grey_question: Cannot Reproduce | Improved compiler error for accessing nonexistant members. |
| [BOO-450](issues/BOO-0450.md) | :white_check_mark: Fixed | Error msg when accessing non-static outer class member |
| [BOO-451](issues/BOO-0451.md) | :white_check_mark: Fixed | ast literals |
| [BOO-452](issues/BOO-0452.md) | :grey_exclamation: Incomplete | Modify Boo codedom in Boo to use AST literals instead. |
| [BOO-453](issues/BOO-0453.md) | :large_blue_circle: Open | Ast literal "block syntax" is broken when not in a binary expression. |
| [BOO-454](issues/BOO-0454.md) | :white_check_mark: Fixed | No compile errors for illegal Constructors/Destructors |
| [BOO-455](issues/BOO-0455.md) | :white_check_mark: Fixed | Boo.Lang.Useful.Attributes.OnceAttribute |
| [BOO-456](issues/BOO-0456.md) | :grey_question: Cannot Reproduce | Internal Compiler error on accessing a method of a return of a property that has a twin |
| [BOO-457](issues/BOO-0457.md) | :arrows_counterclockwise: Reopened | Removal of statically unreachable branches. |
| [BOO-458](issues/BOO-0458.md) | :no_entry_sign: Won't Fix | Scientific notation with negatives. |
| [BOO-459](issues/BOO-0459.md) | :white_check_mark: Fixed | allow float literals with no decimal point |
| [BOO-460](issues/BOO-0460.md) | :white_check_mark: Fixed | Accessing member of outer class |
| [BOO-461](issues/BOO-0461.md) | :large_blue_circle: Open | Deriving enums from any integral type. |
| [BOO-462](issues/BOO-0462.md) | :large_blue_circle: Open | don't require method body when using abstract keyword |
| [BOO-463](issues/BOO-0463.md) | :white_check_mark: Fixed | Support for Int16/UInt16 literals (e.g. Int16.MaxValue) |
| [BOO-464](issues/BOO-0464.md) | :white_check_mark: Fixed | Super keyword attacked by kryptonite. |
| [BOO-465](issues/BOO-0465.md) | :white_check_mark: Fixed | Unhandled exception in Boo Explorer when opening new Interactive Console |
| [BOO-466](issues/BOO-0466.md) | :large_blue_circle: Open | Element syntax. |
| [BOO-467](issues/BOO-0467.md) | :white_check_mark: Fixed | Variables can be set to MaxValue + 1 |
| [BOO-468](issues/BOO-0468.md) | :white_check_mark: Fixed | ulong.MaxValue triggers internal compiler error in booish |
| [BOO-469](issues/BOO-0469.md) | :large_blue_circle: Open | unpacking doesn't work with member refs or slicing expressions |
| [BOO-470](issues/BOO-0470.md) | :white_check_mark: Fixed | Void methods and string extrapolation cause Invalid Program exception |
| [BOO-471](issues/BOO-0471.md) | :large_blue_circle: Open | boo lexer improvement when dealing with "unexpected" characters |
| [BOO-472](issues/BOO-0472.md) | :large_blue_circle: Open | boo eats vowel umlauts |
| [BOO-473](issues/BOO-0473.md) | :no_entry_sign: Won't Fix | No increment/decrement on enum |
| [BOO-474](issues/BOO-0474.md) | :white_check_mark: Fixed | member references to duck casts not converted to invoke runtimeservices |
| [BOO-475](issues/BOO-0475.md) | :white_check_mark: Fixed | try: block without except: or ensure: produces internal compiler error |
| [BOO-476](issues/BOO-0476.md) | :white_check_mark: Fixed | emit custom attributes for constructors |
| [BOO-477](issues/BOO-0477.md) | :large_blue_circle: Open | Ambiguous reference when some public propery has same name as private field |
| [BOO-478](issues/BOO-0478.md) | :large_blue_circle: Open | Better lexical information for Boo Tokens |
| [BOO-479](issues/BOO-0479.md) | :large_blue_circle: Open | Custom filtering for boo lexer tokens |
| [BOO-480](issues/BOO-0480.md) | :white_check_mark: Fixed | BooPrinterVisitor does not output assembly attributes |
| [BOO-481](issues/BOO-0481.md) | :white_check_mark: Fixed | errors with attributes in C# to boo converter |
| [BOO-483](issues/BOO-0483.md) | :large_blue_circle: Open | Throw error if virtual field |
| [BOO-484](issues/BOO-0484.md) | :no_entry_sign: Won't Fix | For loop similar to Basic's for <var> = <start> to <end> [step <step>]: |
| [BOO-485](issues/BOO-0485.md) | :white_check_mark: Fixed | Allow using constants / other enum values as values for enum members |
| [BOO-486](issues/BOO-0486.md) | :large_blue_circle: Open | Shadow/Hide methods |
| [BOO-487](issues/BOO-0487.md) | :white_check_mark: Fixed | Start addin that can compile boo code |
| [BOO-488](issues/BOO-0488.md) | :white_check_mark: Fixed | Add parser for class browser and folding |
| [BOO-489](issues/BOO-0489.md) | :white_check_mark: Fixed | Add resolver for code completion and refactoring |
| [BOO-490](issues/BOO-0490.md) | :no_entry_sign: Won't Fix | Doesn't get the type from .{3}\w+/.Matches(sHTML) |
| [BOO-491](issues/BOO-0491.md) | :large_blue_circle: Open | Ability to mark macro as debug/release |
| [BOO-492](issues/BOO-0492.md) | :no_entry_sign: Won't Fix | Can't compile class which implements IResourceReader |
| [BOO-493](issues/BOO-0493.md) | :white_check_mark: Fixed | Hex character escapes rejected in regex literals |
| [BOO-494](issues/BOO-0494.md) | :link: Duplicate | conditional: alpha < num < beta instread of alpha < num and num < beta |
| [BOO-495](issues/BOO-0495.md) | :white_check_mark: Fixed | ProtectedProperty Attribute |
| [BOO-496](issues/BOO-0496.md) | :white_check_mark: Fixed | Allow for compact statements for block-based expressions |
| [BOO-497](issues/BOO-0497.md) | :no_entry_sign: Won't Fix | Unexpected streamwriter stop |
| [BOO-498](issues/BOO-0498.md) | :large_blue_circle: Open | CollectionAttribute + value type = madness |
| [BOO-499](issues/BOO-0499.md) | :no_entry_sign: Won't Fix | Improved CollectionAttribute |
| [BOO-500](issues/BOO-0500.md) | :white_check_mark: Fixed | self[index] instead of [DefaultMember(Item)] Item(index) |
| [BOO-501](issues/BOO-0501.md) | :white_check_mark: Fixed | slice duck typed arrays and lists |
| [BOO-502](issues/BOO-0502.md) | :large_blue_circle: Open | Adapters for closures fail when using "as" syntax with incorrect number of parameters. |
| [BOO-503](issues/BOO-0503.md) | :white_check_mark: Fixed | Better naming of autogenerated methods that represent closures / callables |
| [BOO-504](issues/BOO-0504.md) | :white_check_mark: Fixed | virtual node visitor |
| [BOO-505](issues/BOO-0505.md) | :large_blue_circle: Open | for key, value in hash |
| [BOO-507](issues/BOO-0507.md) | :white_check_mark: Fixed | Folding events takes sd into an infinite loop |
| [BOO-508](issues/BOO-0508.md) | :white_check_mark: Fixed | allow standalone interpolated strings for templates |
| [BOO-509](issues/BOO-0509.md) | :white_check_mark: Fixed | Custom compiler error and warning messages |
| [BOO-510](issues/BOO-0510.md) | :white_check_mark: Fixed | Error if hit enter in booish |
| [BOO-511](issues/BOO-0511.md) | :white_check_mark: Fixed | #develop should not display boo's "generated" module classes |
| [BOO-512](issues/BOO-0512.md) | :large_blue_circle: Open | Boo.Lang.Useful.Attributes.ResourceFacadeAttribute |
| [BOO-513](issues/BOO-0513.md) | :white_check_mark: Fixed | Boo Form Designer |
| [BOO-514](issues/BOO-0514.md) | :white_check_mark: Fixed | "New Item" doesn't allow for new boo files. |
| [BOO-515](issues/BOO-0515.md) | :white_check_mark: Fixed | Expression resolver thinks " is String.Empty. |
| [BOO-516](issues/BOO-0516.md) | :white_check_mark: Fixed | Tooltips don't work in last line of the document |
| [BOO-517](issues/BOO-0517.md) | :white_check_mark: Fixed | getter / property code generation only outputs C# code. |
| [BOO-518](issues/BOO-0518.md) | :grey_question: Cannot Reproduce | Code completion fails with this code. |
| [BOO-520](issues/BOO-0520.md) | :large_blue_circle: Open | Design by Contract macros |
| [BOO-521](issues/BOO-0521.md) | :no_entry_sign: Won't Fix | Addin not obeying custom highlighting? |
| [BOO-522](issues/BOO-0522.md) | :white_check_mark: Fixed | protected properties emitted as public |
| [BOO-523](issues/BOO-0523.md) | :white_check_mark: Fixed | BooBinding crashes most of #develop. |
| [BOO-524](issues/BOO-0524.md) | :white_check_mark: Fixed | Autocompletion on import doesn't list only namespaces. |
| [BOO-525](issues/BOO-0525.md) | :large_blue_circle: Open | Ast tree information is emptied if there are trailing dots. |
| [BOO-527](issues/BOO-0527.md) | :white_check_mark: Fixed | Make .pdb files work under .NET 1.1 and .NET 2.0 |
| [BOO-528](issues/BOO-0528.md) | :white_check_mark: Fixed | Internal compiler error |
| [BOO-529](issues/BOO-0529.md) | :white_check_mark: Fixed | latest boo does not build with mono 1.1.9.2 |
| [BOO-530](issues/BOO-0530.md) | :white_check_mark: Fixed | booc.exe FAILS to load .NET 2.0 DLLs. |
| [BOO-532](issues/BOO-0532.md) | :white_check_mark: Fixed | Unable to initalize a static field in a struct. |
| [BOO-533](issues/BOO-0533.md) | :no_entry_sign: Won't Fix | Attribute code completion should not be active in method bodies. |
| [BOO-534](issues/BOO-0534.md) | :white_check_mark: Fixed | BeginInvoke overloads are not valid on ms.net 2.0 |
| [BOO-535](issues/BOO-0535.md) | :white_check_mark: Fixed | Code completion for generator syntax. |
| [BOO-536](issues/BOO-0536.md) | :white_check_mark: Fixed | Forms Designer generated code has bad indentation. |
| [BOO-537](issues/BOO-0537.md) | :white_check_mark: Fixed | Addin occasionally freezes during resolving phase. |
| [BOO-538](issues/BOO-0538.md) | :white_check_mark: Fixed | Syntax colorization of doc-strings with slashes goes awry. |
| [BOO-539](issues/BOO-0539.md) | :white_check_mark: Fixed | Forms designer does not hook up events to event handlers. |
| [BOO-540](issues/BOO-0540.md) | :white_check_mark: Fixed | Unable to call blank constructor on a ValueType |
| [BOO-541](issues/BOO-0541.md) | :white_check_mark: Fixed | Reports wrong filename |
| [BOO-542](issues/BOO-0542.md) | :white_check_mark: Fixed | CodeCompletion on interfaces doesn't list inherited Object members. |
| [BOO-543](issues/BOO-0543.md) | :grey_exclamation: Incomplete | I broka the code folding. |
| [BOO-544](issues/BOO-0544.md) | :no_entry_sign: Won't Fix | Boo compiler generating unorthodox code! |
| [BOO-545](issues/BOO-0545.md) | :no_entry_sign: Won't Fix | Global and module level rawindexing/checked |
| [BOO-547](issues/BOO-0547.md) | :large_blue_circle: Open | Assignment inside of conditional: alter the warning message? |
| [BOO-549](issues/BOO-0549.md) | :grey_question: Cannot Reproduce | Incorrect error "BCE0101: The return type of a generator must be either 'System.Collections.IEnumerable' or object" |
| [BOO-550](issues/BOO-0550.md) | :white_check_mark: Fixed | Booc.exe and BooCompiler MUST allow you to sign assemblies. |
| [BOO-551](issues/BOO-0551.md) | :large_blue_circle: Open | Allow tripple single quotes. |
| [BOO-552](issues/BOO-0552.md) | :white_check_mark: Fixed | Allow equality and inequality comparison between enums and integers |
| [BOO-553](issues/BOO-0553.md) | :information_source: Not A Bug | Allow for better detection of Value Types in AST. |
| [BOO-554](issues/BOO-0554.md) | :no_entry_sign: Won't Fix | AbstractAstMacro.InvalidMacroArguments |
| [BOO-555](issues/BOO-0555.md) | :large_blue_circle: Open | Intelligent Multiline Strings |
| [BOO-556](issues/BOO-0556.md) | :large_blue_circle: Open | Stream operator |
| [BOO-557](issues/BOO-0557.md) | :white_check_mark: Fixed | Boo tools fails when in different languages |
| [BOO-558](issues/BOO-0558.md) | :large_blue_circle: Open | Allow advanced array expressions |
| [BOO-559](issues/BOO-0559.md) | :large_blue_circle: Open | Allow assert to return a special Exception |
| [BOO-560](issues/BOO-0560.md) | :large_blue_circle: Open | Inherited and Extension AST Attributes |
| [BOO-561](issues/BOO-0561.md) | :white_check_mark: Fixed | Enumerator returned by "cat" builtin stops if one of the iterators concatenated is empty |
| [BOO-562](issues/BOO-0562.md) | :large_blue_circle: Open | str[-1] gives IndexOutOfRangeException, but str[-1:] doesn't |
| [BOO-563](issues/BOO-0563.md) | :white_check_mark: Fixed | type inference does not detect char type for iteration over strings |
| [BOO-564](issues/BOO-0564.md) | :large_blue_circle: Open | Better extension methods syntax. |
| [BOO-565](issues/BOO-0565.md) | :white_check_mark: Fixed | emit specialname attribute for special methods |
| [BOO-567](issues/BOO-0567.md) | :white_check_mark: Fixed | emit debug info for separate files |
| [BOO-568](issues/BOO-0568.md) | :large_blue_circle: Open | More detail for properties in code completion |
| [BOO-569](issues/BOO-0569.md) | :white_check_mark: Fixed | Simple code fails to build. |
| [BOO-570](issues/BOO-0570.md) | :large_blue_circle: Open | ANTLR - semantic predicate results in invalid '!' operator; misplaced imports |
| [BOO-571](issues/BOO-0571.md) | :white_check_mark: Fixed | bad op_Member (in/not in) precedence |
| [BOO-572](issues/BOO-0572.md) | :large_blue_circle: Open | BooCompiler does not recognize InternalsVisibleToAttribute |
| [BOO-577](issues/BOO-0577.md) | :white_check_mark: Fixed | Extract binding of enum members into its own step. |
| [BOO-578](issues/BOO-0578.md) | :white_check_mark: Fixed | AutoFlags attribute to automatically set enum values. |
| [BOO-579](issues/BOO-0579.md) | :white_check_mark: Fixed | line numbers off in wsaboo |
| [BOO-580](issues/BOO-0580.md) | :large_blue_circle: Open | isa operator should work with ReferenceExpression |
| [BOO-581](issues/BOO-0581.md) | :large_blue_circle: Open | Allow typeof() to work with expressions as a substitute to the GetType() method |
| [BOO-582](issues/BOO-0582.md) | :large_blue_circle: Open | Addin for #dev to see the code a Boo file will generate |
| [BOO-583](issues/BOO-0583.md) | :white_check_mark: Fixed | optimize ast literal processing |
| [BOO-584](issues/BOO-0584.md) | :white_check_mark: Fixed | booc nant task should have default deb ug setting as true to be compatible with command line booc |
| [BOO-585](issues/BOO-0585.md) | :white_check_mark: Fixed | twilight zone bug: closures are processed more than once |
| [BOO-589](issues/BOO-0589.md) | :white_check_mark: Fixed | Tooltip information fails when a property is named after a type. |
| [BOO-590](issues/BOO-0590.md) | :white_check_mark: Fixed | Position of files messes up ProcessMethodBodiesWithDuckTyping for properties |
| [BOO-591](issues/BOO-0591.md) | :white_check_mark: Fixed | Name resolution fails if a type in the current namespace has the same name as one in an imported namespace |
| [BOO-593](issues/BOO-0593.md) | :no_entry_sign: Won't Fix | static classes |
| [BOO-595](issues/BOO-0595.md) | :white_check_mark: Fixed | binary operator overloading with ducky should invoke operator directly instead of calling QuackInvoke() |
| [BOO-596](issues/BOO-0596.md) | :white_check_mark: Fixed | treat any IQuackFu implementing class as duck (even when -ducky is not set) |
| [BOO-597](issues/BOO-0597.md) | :white_check_mark: Fixed | extension methods |
| [BOO-599](issues/BOO-0599.md) | :white_check_mark: Fixed | booish doesn't work with .net 2.0 |
| [BOO-600](issues/BOO-0600.md) | :white_check_mark: Fixed | op_Implicit not being called for duck typed something or other's. |
| [BOO-601](issues/BOO-0601.md) | :white_check_mark: Fixed | indexed properties in interfaces |
| [BOO-602](issues/BOO-0602.md) | :white_check_mark: Fixed | search inherited interfaces for DefaultMember |
| [BOO-603](issues/BOO-0603.md) | :white_check_mark: Fixed | GetSlice doesn't work with non-indexed properties that return indexable object |
| [BOO-604](issues/BOO-0604.md) | :white_check_mark: Fixed | any() all() functions |
| [BOO-605](issues/BOO-0605.md) | :white_check_mark: Fixed | Varargs messes up if there are multiple methods with the same name. |
| [BOO-606](issues/BOO-0606.md) | :white_check_mark: Fixed | neither /\+/ or @/\+/ works, but regex("""\+""") does. |
| [BOO-607](issues/BOO-0607.md) | :white_check_mark: Fixed | Add [DefaultMember] to class that has inherited default indexers |
| [BOO-608](issues/BOO-0608.md) | :white_check_mark: Fixed | negative numbers not working as arguments to attribute properties |
| [BOO-609](issues/BOO-0609.md) | :white_check_mark: Fixed | Wildcard in references of NAnt booc task give errors. |
| [BOO-610](issues/BOO-0610.md) | :white_check_mark: Fixed | Optional return on inline closures. |
| [BOO-612](issues/BOO-0612.md) | :white_check_mark: Fixed | Cannot use assignments to byref parameters as expressions |
| [BOO-613](issues/BOO-0613.md) | :white_check_mark: Fixed | Exception thrown on double click |
| [BOO-614](issues/BOO-0614.md) | :white_check_mark: Fixed | type array literal |
| [BOO-615](issues/BOO-0615.md) | :no_entry_sign: Won't Fix | remove grouping by 3 constraint from numeric literals |
| [BOO-616](issues/BOO-0616.md) | :large_blue_circle: Open | Improve highlighting options. |
| [BOO-617](issues/BOO-0617.md) | :white_check_mark: Fixed | allow bitwise negation operator (~) to be used with enums |
| [BOO-618](issues/BOO-0618.md) | :white_check_mark: Fixed | Allow implicit conversion from enums to bool (just like integers) |
| [BOO-619](issues/BOO-0619.md) | :white_check_mark: Fixed | Shortcuts to interfaces |
| [BOO-620](issues/BOO-0620.md) | :large_blue_circle: Open | better type inference for unpack statement |
| [BOO-621](issues/BOO-0621.md) | :large_blue_circle: Open | Safe version of isa |
| [BOO-622](issues/BOO-0622.md) | :white_check_mark: Fixed | extension methods should be allowed to overload existing methods |
| [BOO-623](issues/BOO-0623.md) | :white_check_mark: Fixed | emit error when an extension method tries to redefine an existing member |
| [BOO-624](issues/BOO-0624.md) | :large_blue_circle: Open | Java-style inner classes |
| [BOO-625](issues/BOO-0625.md) | :white_check_mark: Fixed | Internal compiler error when trying to override non virtual method with an explicit interface implementation |
| [BOO-626](issues/BOO-0626.md) | :white_check_mark: Fixed | Cyclic inheritance error on interfaces |
| [BOO-627](issues/BOO-0627.md) | :white_check_mark: Fixed | BooPrinterVisitor generates invalid code for typed array literals with one element |
| [BOO-628](issues/BOO-0628.md) | :white_check_mark: Fixed | Code generation generating C# code. |
| [BOO-629](issues/BOO-0629.md) | :white_check_mark: Fixed | Variable scope. |
| [BOO-630](issues/BOO-0630.md) | :white_check_mark: Fixed | #develop addin doesn't handle dangling commas |
| [BOO-631](issues/BOO-0631.md) | :no_entry_sign: Won't Fix | remove extraneous end statements in properties |
| [BOO-632](issues/BOO-0632.md) | :white_check_mark: Fixed | Accessing protected fields failure. |
| [BOO-633](issues/BOO-0633.md) | :white_check_mark: Fixed | Allow Unicode identifiers |
| [BOO-634](issues/BOO-0634.md) | :large_blue_circle: Open | Add several helper property / methods for Boo.Lang.List |
| [BOO-635](issues/BOO-0635.md) | :white_check_mark: Fixed | Unmarked base class methods not recognized as final |
| [BOO-636](issues/BOO-0636.md) | :white_check_mark: Fixed | Using equal sign (=) in attribute causes explosivo. |
| [BOO-637](issues/BOO-0637.md) | :arrows_counterclockwise: Reopened | Boo does not check to see wheither a parameterless constructor exists in inherited class before generating code for it |
| [BOO-638](issues/BOO-0638.md) | :white_check_mark: Fixed | and operator precedence |
| [BOO-639](issues/BOO-0639.md) | :grey_question: Cannot Reproduce | #develop 2.0 addin broken |
| [BOO-640](issues/BOO-0640.md) | :white_check_mark: Fixed | Variable assignments within conditionals |
| [BOO-641](issues/BOO-0641.md) | :large_blue_circle: Open | regular expression interferes with math |
| [BOO-642](issues/BOO-0642.md) | :white_check_mark: Fixed | Internal compiler error when using value types inside generator methods |
| [BOO-643](issues/BOO-0643.md) | :white_check_mark: Fixed | ref overloads problem prevents calling CLI methods |
| [BOO-644](issues/BOO-0644.md) | :white_check_mark: Fixed | implicit bool conversion operator not called in duck typing mode |
| [BOO-645](issues/BOO-0645.md) | :white_check_mark: Fixed | Build crash at generate-ast task |
| [BOO-646](issues/BOO-0646.md) | :white_check_mark: Fixed | byref overloading |
| [BOO-647](issues/BOO-0647.md) | :white_check_mark: Fixed | P/Invokes as instance methods generate bad IL |
| [BOO-648](issues/BOO-0648.md) | :white_check_mark: Fixed | Boo allows non-unique parameter names -- a bug |
| [BOO-649](issues/BOO-0649.md) | :white_check_mark: Fixed | Can only link /usr/lib |
| [BOO-650](issues/BOO-0650.md) | :white_check_mark: Fixed | type inference error when enumeratoritemtype not yet visited |
| [BOO-651](issues/BOO-0651.md) | :white_check_mark: Fixed | Check both types for explicit conversion operator |
| [BOO-652](issues/BOO-0652.md) | :large_blue_circle: Open | Do not allow reserved function names in modules. |
| [BOO-653](issues/BOO-0653.md) | :white_check_mark: Fixed | Creating a new class without a file extension does not put the build action to compile. |
| [BOO-654](issues/BOO-0654.md) | :white_check_mark: Fixed | "Run Tests in Debugger" / "Run with NCover" / etc fail with warnings. |
| [BOO-655](issues/BOO-0655.md) | :white_check_mark: Fixed | allowing initializing final fields from constructor |
| [BOO-656](issues/BOO-0656.md) | :white_check_mark: Fixed | Boo is stupid when dealing with virtual methods passed by reference |
| [BOO-657](issues/BOO-0657.md) | :white_check_mark: Fixed | ambiguous ref with multiple imports |
| [BOO-658](issues/BOO-0658.md) | :white_check_mark: Fixed | "Run with code coverage" crashes. |
| [BOO-659](issues/BOO-0659.md) | :large_blue_circle: Open | Deployment of Boo-based software without Boo.Lang.dll dependency |
| [BOO-660](issues/BOO-0660.md) | :white_check_mark: Fixed | Upgrade #develop to use new Boo.Lang.CodeDom |
| [BOO-661](issues/BOO-0661.md) | :grey_question: Cannot Reproduce | Inner type dependancies broken with .NET 2.0 |
| [BOO-662](issues/BOO-0662.md) | :white_check_mark: Fixed | Assignment to properties with indexes broken and won't compile on duck types |
| [BOO-663](issues/BOO-0663.md) | :white_check_mark: Fixed | 2 tests fail on .net 2 |
| [BOO-664](issues/BOO-0664.md) | :large_blue_circle: Open | Change boo codedom to call booc.exe externally |
| [BOO-665](issues/BOO-0665.md) | :large_blue_circle: Open | partial compilation |
| [BOO-666](issues/BOO-0666.md) | :grey_question: Cannot Reproduce | allow protected internal classes |
| [BOO-667](issues/BOO-0667.md) | :white_check_mark: Fixed | Allow special characters in startof variables |
| [BOO-668](issues/BOO-0668.md) | :large_blue_circle: Open | Shadowing methods/fields/properties |
| [BOO-669](issues/BOO-0669.md) | :large_blue_circle: Open | Reference and output modules |
| [BOO-670](issues/BOO-0670.md) | :large_blue_circle: Open | Rewrite test framework to use specified runtime |
| [BOO-671](issues/BOO-0671.md) | :white_check_mark: Fixed | Update boo codedom for .net 2 |
| [BOO-672](issues/BOO-0672.md) | :white_check_mark: Fixed | Parser error on one line scritps in WSA Boo |
| [BOO-673](issues/BOO-0673.md) | :large_blue_circle: Open | parser issues with semicolons and newlines |
| [BOO-674](issues/BOO-0674.md) | :white_check_mark: Fixed | assembly loading issues |
| [BOO-675](issues/BOO-0675.md) | :white_check_mark: Fixed | Smarter delegate adaption |
| [BOO-676](issues/BOO-0676.md) | :white_check_mark: Fixed | target different frameworks with booc nant task |
| [BOO-677](issues/BOO-0677.md) | :white_check_mark: Fixed | variable argument lists prevent callables from being invoked via dictionaries |
| [BOO-678](issues/BOO-0678.md) | :no_entry_sign: Won't Fix | booc.exe always uses boo dlls from gac, even if out of date |
| [BOO-679](issues/BOO-0679.md) | :white_check_mark: Fixed | Builtins to detect mono and platform |
| [BOO-680](issues/BOO-0680.md) | :white_check_mark: Fixed | Add "compiling" tab to #develop Boo Project properties page |
| [BOO-681](issues/BOO-0681.md) | :white_check_mark: Fixed | Boo compiler not looking in correct location when signing assembly? |
| [BOO-682](issues/BOO-0682.md) | :white_check_mark: Fixed | Passing -debug- to booc still generates pdb file |
| [BOO-683](issues/BOO-0683.md) | :white_check_mark: Fixed | Compact blocks cannot contain assignment |
| [BOO-684](issues/BOO-0684.md) | :white_check_mark: Fixed | Compiler error with generator expression and test for null |
| [BOO-685](issues/BOO-0685.md) | :white_check_mark: Fixed | Private fields of base class should not interfere with local variable names in derived classes |
| [BOO-686](issues/BOO-0686.md) | :white_check_mark: Fixed | Code generation fails in #develop 2 |
| [BOO-687](issues/BOO-0687.md) | :white_check_mark: Fixed | Add -keyfile option to specify assembly signing key |
| [BOO-688](issues/BOO-0688.md) | :white_check_mark: Fixed | Project properties page for assembly signing. |
| [BOO-689](issues/BOO-0689.md) | :grey_exclamation: Incomplete | Node not parsing correctly whith multiple macro blocks |
| [BOO-690](issues/BOO-0690.md) | :white_check_mark: Fixed | Cannot compile source file called 1.boo |
| [BOO-691](issues/BOO-0691.md) | :white_check_mark: Fixed | A class that implements an interface cannot rely on inherited methods? |
| [BOO-692](issues/BOO-0692.md) | :no_entry_sign: Won't Fix | Built-in value type conversions |
| [BOO-693](issues/BOO-0693.md) | :large_blue_circle: Open | Warning on loss of precision for builtin type conversions |
| [BOO-694](issues/BOO-0694.md) | :white_check_mark: Fixed | Booi does not forward exit code from applications |
| [BOO-695](issues/BOO-0695.md) | :large_blue_circle: Open | Can't subtract two variables |
| [BOO-696](issues/BOO-0696.md) | :white_check_mark: Fixed | This code crashes #develop |
| [BOO-697](issues/BOO-0697.md) | :white_check_mark: Fixed | comparing float/double against zero literal results in invalid IL |
| [BOO-698](issues/BOO-0698.md) | :white_check_mark: Fixed | return from constructor |
| [BOO-699](issues/BOO-0699.md) | :no_entry_sign: Won't Fix | Cannot cast from String to Int |
| [BOO-700](issues/BOO-0700.md) | :grey_question: Cannot Reproduce | IQuackFu inherited class constructor bug |
| [BOO-701](issues/BOO-0701.md) | :white_check_mark: Fixed | pass array elements byref to external method |
| [BOO-702](issues/BOO-0702.md) | :white_check_mark: Fixed | Compiler should use builtin type names in error messages |
| [BOO-703](issues/BOO-0703.md) | :white_check_mark: Fixed | Compiler warning on implicit return statement |
| [BOO-704](issues/BOO-0704.md) | :white_check_mark: Fixed | booish fails to resolve assembly when block of code creates instance of a dynamically defined class |
| [BOO-705](issues/BOO-0705.md) | :white_check_mark: Fixed | System.AccessViolation when using shl or shr |
| [BOO-706](issues/BOO-0706.md) | :large_blue_circle: Open | Print doesn't print scandic letters |
| [BOO-707](issues/BOO-0707.md) | :white_check_mark: Fixed | Boo does not support numeric promotion to UIntPtr! |
| [BOO-708](issues/BOO-0708.md) | :large_blue_circle: Open | Support for PEP-263 like encoding specifications |
| [BOO-709](issues/BOO-0709.md) | :white_check_mark: Fixed | Unsightly C-like "order of importance" when defining and consuming System.Attribute derived classes. |
| [BOO-710](issues/BOO-0710.md) | :white_check_mark: Fixed | Boo doesn't emit attributes for enum members |
| [BOO-711](issues/BOO-0711.md) | :large_blue_circle: Open | Unnecessary widening of expression types in bitwise operators |
| [BOO-712](issues/BOO-0712.md) | :large_blue_circle: Open | Support for options after regex |
| [BOO-713](issues/BOO-0713.md) | :white_check_mark: Fixed | Oddness with Boo and DataGridView.Columns.AddRange |
| [BOO-714](issues/BOO-0714.md) | :white_check_mark: Fixed | broken 'for ... in range(...)' statement |
| [BOO-715](issues/BOO-0715.md) | :construction: In Progress | Step implementation for index slicing |
| [BOO-716](issues/BOO-0716.md) | :white_check_mark: Fixed | Cannot compare two int32's with '<' or '>' operator |
| [BOO-717](issues/BOO-0717.md) | :white_check_mark: Fixed | Initialization of Object assigned to an variable isn't working properly |
| [BOO-718](issues/BOO-0718.md) | :white_check_mark: Fixed | Creating value type objects in booish throws exception |
| [BOO-719](issues/BOO-0719.md) | :white_check_mark: Fixed | property override depends on compilation order |
| [BOO-720](issues/BOO-0720.md) | :large_blue_circle: Open | Code completion on unpacked variables |
| [BOO-721](issues/BOO-0721.md) | :white_check_mark: Fixed | BooCodeDom CodeArrayCreateExpression Bug |
| [BOO-722](issues/BOO-0722.md) | :large_blue_circle: Open | DLL generation on PPC problem |
| [BOO-723](issues/BOO-0723.md) | :white_check_mark: Fixed | Boo doesn't check for inherited indexers early enough |
| [BOO-724](issues/BOO-0724.md) | :white_check_mark: Fixed | Private fields conflict with same named fields in child class |
| [BOO-725](issues/BOO-0725.md) | :white_check_mark: Fixed | Boxing enum values to System.Enum does not work |
| [BOO-726](issues/BOO-0726.md) | :white_check_mark: Fixed | Booi does not allow parameterless entry point |
| [BOO-727](issues/BOO-0727.md) | :white_check_mark: Fixed | CodeDom doesn't use the char() macro for creating characters. |
| [BOO-728](issues/BOO-0728.md) | :large_blue_circle: Open | BooComparer doesn't ensure that two objects are of the same type before calling CompareTo |
| [BOO-729](issues/BOO-0729.md) | :white_check_mark: Fixed | byref overriding regression |
| [BOO-730](issues/BOO-0730.md) | :white_check_mark: Fixed | BooPrinterVisitor outputs invalid definitions for interfaces |
| [BOO-731](issues/BOO-0731.md) | :large_blue_circle: Open | Problems with Warning BCW0006 |
| [BOO-732](issues/BOO-0732.md) | :large_blue_circle: Open | crash when typing in source file |
| [BOO-733](issues/BOO-0733.md) | :white_check_mark: Fixed | non-obvious behaviour with type inference and integer saturation |
| [BOO-734](issues/BOO-0734.md) | :no_entry_sign: Won't Fix | Boo doesn't recognize the right overload |
| [BOO-735](issues/BOO-0735.md) | :white_check_mark: Fixed | Unhandled exception / ASP.Net pages in Boo / CodeDom error / Value cannot be null. Parameter name: e |
| [BOO-736](issues/BOO-0736.md) | :white_check_mark: Fixed | Booc crashes because of stack overflow |
| [BOO-737](issues/BOO-0737.md) | :large_blue_circle: Open | Side-effects of operators should not be ignored |
| [BOO-738](issues/BOO-0738.md) | :large_blue_circle: Open | Compiler locks up when using MarshalAs attribute in a struct |
| [BOO-739](issues/BOO-0739.md) | :white_check_mark: Fixed | static fields are initialized after static constructor |
| [BOO-740](issues/BOO-0740.md) | :white_check_mark: Fixed | reading write-only property - compiler error |
| [BOO-741](issues/BOO-0741.md) | :white_check_mark: Fixed | booish not reporting output and errors |
| [BOO-742](issues/BOO-0742.md) | :white_check_mark: Fixed | Current Generic support breaks name resolution |
| [BOO-744](issues/BOO-0744.md) | :large_blue_circle: Open | Unable to define/consume namespace Runtime.* |
| [BOO-745](issues/BOO-0745.md) | :large_blue_circle: Open | booish, list comprehension as statement is a syntax error |
| [BOO-746](issues/BOO-0746.md) | :large_blue_circle: Open | make boo executables use the latest runtime version available in the system through configuration files |
| [BOO-747](issues/BOO-0747.md) | :white_check_mark: Fixed | duck typings fails to assign to array field element |
| [BOO-748](issues/BOO-0748.md) | :white_check_mark: Fixed | Problem with typeof() in custom attributes |
| [BOO-749](issues/BOO-0749.md) | :large_blue_circle: Open | PATCH: Support fro embedded manifest resources on .NET 2.0 |
| [BOO-750](issues/BOO-0750.md) | :white_check_mark: Fixed | Embedding resources with NAnt <booc> task |
| [BOO-751](issues/BOO-0751.md) | :large_blue_circle: Open | allow compact property getters/setters |
| [BOO-752](issues/BOO-0752.md) | :arrows_counterclockwise: Reopened | functional programing from Python |
| [BOO-753](issues/BOO-0753.md) | :white_check_mark: Fixed | cannot call params super constructor |
| [BOO-754](issues/BOO-0754.md) | :white_check_mark: Fixed | Large integer expressions can cause crashes |
| [BOO-755](issues/BOO-0755.md) | :white_check_mark: Fixed | Type inference for IEnumerable of T |
| [BOO-756](issues/BOO-0756.md) | :white_check_mark: Fixed | Extending generic types |
| [BOO-757](issues/BOO-0757.md) | :white_check_mark: Fixed | Generic type references and generic type reference expressions |
| [BOO-758](issues/BOO-0758.md) | :white_check_mark: Fixed | Generic instance for internal types |
| [BOO-759](issues/BOO-0759.md) | :arrows_counterclockwise: Reopened | Invalid IL for generator methods whose yield type is a generic parameter |
| [BOO-760](issues/BOO-0760.md) | :white_check_mark: Fixed | Generic callable instantiation |
| [BOO-761](issues/BOO-0761.md) | :white_check_mark: Fixed | Implementing generic interfaces |
| [BOO-762](issues/BOO-0762.md) | :white_check_mark: Fixed | overriding generic members |
| [BOO-763](issues/BOO-0763.md) | :construction: In Progress | Defining new generic types |
| [BOO-764](issues/BOO-0764.md) | :no_entry_sign: Won't Fix | Stack overflow when calling base method from derived class when base class implements an interface |
| [BOO-765](issues/BOO-0765.md) | :white_check_mark: Fixed | Regression when deciding which method to invoke. |
| [BOO-766](issues/BOO-0766.md) | :white_check_mark: Fixed | IQuackFu doesn't work on ctor declaration |
| [BOO-767](issues/BOO-0767.md) | :white_check_mark: Fixed | Shortened attribute names can't have namespace alias prefix |
| [BOO-768](issues/BOO-0768.md) | :white_check_mark: Fixed | typo in BCE0023 error message: "appropriate" mispelled as "apropriate" |
| [BOO-770](issues/BOO-0770.md) | :white_check_mark: Fixed | BCE0022: Boo.Lang.Compiler.CompilerError: Cannot convert '?' to 'unknown' - error due to placement of static constructs in a class |
| [BOO-771](issues/BOO-0771.md) | :large_blue_circle: Open | Embedded Resource broken - BCE0011: An error occurred during the execution of the step 'Boo.Lang.Compiler.Steps.EmitAssembly': 'Stream is not a valid resource file.' |
| [BOO-772](issues/BOO-0772.md) | :large_blue_circle: Open | Internal compiler error while adding event |
| [BOO-773](issues/BOO-0773.md) | :large_blue_circle: Open | Invalid labels generated during C#=>boo conversion |
| [BOO-774](issues/BOO-0774.md) | :large_blue_circle: Open | NDoc-style comments are stripped during C#=>boo conversion |
| [BOO-775](issues/BOO-0775.md) | :white_check_mark: Fixed | ~ (bitwise not operator) cannot be used on an enum |
| [BOO-776](issues/BOO-0776.md) | :large_blue_circle: Open | Should be able to subtract chars |
| [BOO-777](issues/BOO-0777.md) | :white_check_mark: Fixed | Consuming generic methods |
| [BOO-779](issues/BOO-0779.md) | :white_check_mark: Fixed | Use generic IEnumerable interface for compiling for loops when applicable |
| [BOO-780](issues/BOO-0780.md) | :white_check_mark: Fixed | Incorrect type inference for IEnumerable of KeyValuePair[of Person, Person] |
| [BOO-783](issues/BOO-0783.md) | :large_blue_circle: Open | Slicing a multidimensional array only works if you specify explicit bounds for all dimensions |
| [BOO-784](issues/BOO-0784.md) | :large_blue_circle: Open | Can't use negative index in a multidimensional array |
| [BOO-785](issues/BOO-0785.md) | :white_check_mark: Fixed | Internal compiler error with events on mixed generic types |
| [BOO-786](issues/BOO-0786.md) | :white_check_mark: Fixed | SingletonAttribute thread-safety and lazy instantiation |
| [BOO-787](issues/BOO-0787.md) | :white_check_mark: Fixed | Internal compiler error when referencing inherited members on mixed generic types |
| [BOO-788](issues/BOO-0788.md) | :white_check_mark: Fixed | IQuackFu.QuackGet and IQuackFu.QuackSet should support parameterized properties (slicing) |
| [BOO-789](issues/BOO-0789.md) | :white_check_mark: Fixed | Compiler should warn but automatically create stubs for non implemented interfaces methods |
| [BOO-790](issues/BOO-0790.md) | :white_check_mark: Fixed | Compiler should warn but automatically create stubs for non implemented inherited abstract methods |
| [BOO-791](issues/BOO-0791.md) | :white_check_mark: Fixed | Generics: Compiler can't infer type for arrays of generic types |
| [BOO-792](issues/BOO-0792.md) | :white_check_mark: Fixed | assignment to field member with the same name as loop variable confuses the compiler |
| [BOO-793](issues/BOO-0793.md) | :white_check_mark: Fixed | Compiler does not emit gendarme-compliant IL when using interpolation expressions |
| [BOO-794](issues/BOO-0794.md) | :white_check_mark: Fixed | Incorrect handling of ref parameters for mixed generic types |
| [BOO-795](issues/BOO-0795.md) | :question: Unknown | *(no title captured)* |
| [BOO-796](issues/BOO-0796.md) | :white_check_mark: Fixed | BCE0055 fired during compilation starting from rev 2393 (generics generators) |
| [BOO-797](issues/BOO-0797.md) | :white_check_mark: Fixed | Strong versioning for Boo assemblies |
| [BOO-798](issues/BOO-0798.md) | :large_blue_circle: Open | "property" keyword macro. |
| [BOO-799](issues/BOO-0799.md) | :white_check_mark: Fixed | range builtin does not support multiple iterations |
| [BOO-800](issues/BOO-0800.md) | :white_check_mark: Fixed | Invalid program error on 'void' generators |
| [BOO-801](issues/BOO-0801.md) | :white_check_mark: Fixed | Debug symbols are emitted multiple times for a "for in" statement. |
| [BOO-802](issues/BOO-0802.md) | :white_check_mark: Fixed | CodeDom implementation is not aware of generics |
| [BOO-803](issues/BOO-0803.md) | :large_blue_circle: Open | Generic list and hash builtins |
| [BOO-804](issues/BOO-0804.md) | :white_check_mark: Fixed | Making booc consuming/producing CLI compiler-related attributes |
| [BOO-805](issues/BOO-0805.md) | :white_check_mark: Fixed | Can't use == on nullable types |
| [BOO-806](issues/BOO-0806.md) | :white_check_mark: Fixed | volatile fields |
| [BOO-807](issues/BOO-0807.md) | :white_check_mark: Fixed | Issues with using nullable types in Boo |
| [BOO-808](issues/BOO-0808.md) | :white_check_mark: Fixed | Add a -checked(+/-) option to booc |
| [BOO-809](issues/BOO-0809.md) | :white_check_mark: Fixed | Compiler error when overriding virtua generator method |
| [BOO-810](issues/BOO-0810.md) | :large_blue_circle: Open | Compiler should emit an error when trying to define a generator which takes ByRef or Out arguments. |
| [BOO-811](issues/BOO-0811.md) | :white_check_mark: Fixed | Race condition in GetBoolConverter |
| [BOO-812](issues/BOO-0812.md) | :white_check_mark: Fixed | Static method incorrectly tries to access a non-static class member |
| [BOO-813](issues/BOO-0813.md) | :white_check_mark: Fixed | Anonymous callable types are incompatible with generic type references |
| [BOO-814](issues/BOO-0814.md) | :construction: In Progress | Type inference for generic method invocations |
| [BOO-815](issues/BOO-0815.md) | :white_check_mark: Fixed | except clause variable names are not being checked by the compiler |
| [BOO-816](issues/BOO-0816.md) | :large_blue_circle: Open | A standalone \$ incorrectly escapes in triple quoted strings |
| [BOO-817](issues/BOO-0817.md) | :white_check_mark: Fixed | issue an error "event can only be invoked from within the class that declared it" |
| [BOO-818](issues/BOO-0818.md) | :white_check_mark: Fixed | Shorthand syntax for Nullable of T, like T? in C#. |
| [BOO-819](issues/BOO-0819.md) | :white_check_mark: Fixed | Disallow comparing static ref to function with not static ref |
| [BOO-820](issues/BOO-0820.md) | :white_check_mark: Fixed | Honor generic parameter constraints when constructing generic types |
| [BOO-821](issues/BOO-0821.md) | :white_check_mark: Fixed | Error checking: Cant return from ensure block |
| [BOO-822](issues/BOO-0822.md) | :white_check_mark: Fixed | Interpretator incorrectly adds two nullable decimals |
| [BOO-823](issues/BOO-0823.md) | :white_check_mark: Fixed | Compiler messages has several misspellings |
| [BOO-824](issues/BOO-0824.md) | :link: Duplicate | Generic and non-generic methods conflict during method invocation resolution |
| [BOO-825](issues/BOO-0825.md) | :white_check_mark: Fixed | generators compiled with .net 1.1 boo binaries dont run with the runtime compiled for .net 2.0 |
| [BOO-826](issues/BOO-0826.md) | :white_check_mark: Fixed | Internal compiler error when using a generic method invocation as the target of a member reference expression |
| [BOO-827](issues/BOO-0827.md) | :white_check_mark: Fixed | InvalidCastException when calling overloaded function with duck argument |
| [BOO-828](issues/BOO-0828.md) | :white_check_mark: Fixed | slice in duck typing mode doesn't work with a non indexed property |
| [BOO-829](issues/BOO-0829.md) | :white_check_mark: Fixed | Overload resolution and argument conversion is not the same in duck typing mode |
| [BOO-830](issues/BOO-0830.md) | :large_blue_circle: Open | Substraction operator for arrays (+ bug on addition operator?) |
| [BOO-831](issues/BOO-0831.md) | :white_check_mark: Fixed | CompilerGeneratedExtensions.BeginInvoke is ambiguous |
| [BOO-832](issues/BOO-0832.md) | :construction: In Progress | Defining new generic methods |
| [BOO-833](issues/BOO-0833.md) | :white_check_mark: Fixed | Compiler thinks a property is write-only when only the setter is overriden |
| [BOO-834](issues/BOO-0834.md) | :white_check_mark: Fixed | include booish2/Interpreter2 in default build & add option to delimit suggestions with newlines |
| [BOO-835](issues/BOO-0835.md) | :white_check_mark: Fixed | DSL-friendly method syntax |
| [BOO-836](issues/BOO-0836.md) | :white_check_mark: Fixed | WSA Boo "end" keyword required for some blocks and not others |
| [BOO-837](issues/BOO-0837.md) | :large_blue_circle: Open | Avoid emitting superfluous st/ld opcodes |
| [BOO-838](issues/BOO-0838.md) | :large_blue_circle: Open | Boo Windows Installer |
| [BOO-839](issues/BOO-0839.md) | :large_blue_circle: Open | Boo Docbook documentation |
| [BOO-840](issues/BOO-0840.md) | :large_blue_circle: Open | assert macro does not accept certain expressions |
| [BOO-841](issues/BOO-0841.md) | :white_check_mark: Fixed | Meta programming facilities: quasi-quotation ([\| \|]) and splice ($) |
| [BOO-842](issues/BOO-0842.md) | :construction: In Progress | meta method code reification |
| [BOO-843](issues/BOO-0843.md) | :large_blue_circle: Open | Members should be directly assignable in a for loop |
| [BOO-844](issues/BOO-0844.md) | :white_check_mark: Fixed | can not override property setter |
| [BOO-845](issues/BOO-0845.md) | :link: Duplicate | Cannot emit generator methods whose yield type is a generic parameter |
| [BOO-846](issues/BOO-0846.md) | :white_check_mark: Fixed | Internal Generic Types: Parser Support |
| [BOO-847](issues/BOO-0847.md) | :large_blue_circle: Open | Internal Generic Methods: Code Builder support |
| [BOO-848](issues/BOO-0848.md) | :white_check_mark: Fixed | Internal Generic Types: Type system support |
| [BOO-849](issues/BOO-0849.md) | :white_check_mark: Fixed | Internal Generic Types: Emitter support |
| [BOO-850](issues/BOO-0850.md) | :large_blue_circle: Open | Internal Generic Types: Code Builder support |
| [BOO-851](issues/BOO-0851.md) | :large_blue_circle: Open | Automatic interface stubbing can create method conflicts |
| [BOO-852](issues/BOO-0852.md) | :white_check_mark: Fixed | Internal compiler error when subscribing to event on subclassed generic type |
| [BOO-853](issues/BOO-0853.md) | :construction: In Progress | Internal Generic Types: Correct handling of nested types inside generic types |
| [BOO-854](issues/BOO-0854.md) | :large_blue_circle: Open | Anonymous callable types fail when signature contains generic parameters |
| [BOO-855](issues/BOO-0855.md) | :link: Duplicate | Nested types enclosed in internal generic types |
| [BOO-857](issues/BOO-0857.md) | :white_check_mark: Fixed | boobinding does not compile |
| [BOO-858](issues/BOO-0858.md) | :large_blue_circle: Open | code completion for meta methods |
| [BOO-859](issues/BOO-0859.md) | :no_entry_sign: Won't Fix | Ternary operator in print statements doesn't work |
| [BOO-860](issues/BOO-0860.md) | :white_check_mark: Fixed | (enum + string) generates invalid code |
| [BOO-861](issues/BOO-0861.md) | :question: Unknown | *(no title captured)* |
| [BOO-862](issues/BOO-0862.md) | :white_check_mark: Fixed | boo generates invalid code for short circuited operations on float values |
| [BOO-863](issues/BOO-0863.md) | :white_check_mark: Fixed | ObsoleteAttribute support |
| [BOO-864](issues/BOO-0864.md) | :white_check_mark: Fixed | Error implementing interface inheriting interface implemented by base class |
| [BOO-865](issues/BOO-0865.md) | :white_check_mark: Fixed | property attribute doesn't handle field named 'value' properly |
| [BOO-866](issues/BOO-0866.md) | :white_check_mark: Fixed | Type reference to inner class generates a '+' instead of '.' |
| [BOO-867](issues/BOO-0867.md) | :white_check_mark: Fixed | compiler doesnt check type compatibility for null field initializer |
| [BOO-868](issues/BOO-0868.md) | :large_blue_circle: Open | slicing for iterators |
| [BOO-869](issues/BOO-0869.md) | :white_check_mark: Fixed | wrong type inferred for null field initializer |
| [BOO-870](issues/BOO-0870.md) | :white_check_mark: Fixed | parser should not require the 'L' suffix to parse long literals |
| [BOO-871](issues/BOO-0871.md) | :white_check_mark: Fixed | booish fails to display dictionary that contains DynamicMethod |
| [BOO-872](issues/BOO-0872.md) | :white_check_mark: Fixed | better name for closure methods |
| [BOO-873](issues/BOO-0873.md) | :white_check_mark: Fixed | extension methods should be preferred over non accessible members |
| [BOO-874](issues/BOO-0874.md) | :white_check_mark: Fixed | compiler doesn't generate debug information for duck typed call sites |
| [BOO-875](issues/BOO-0875.md) | :white_check_mark: Fixed | SingletonAttribute generates code that FxCop does not like |
| [BOO-876](issues/BOO-0876.md) | :white_check_mark: Fixed | Exception Handling: Remove hidden '__exception' variable |
| [BOO-877](issues/BOO-0877.md) | :white_check_mark: Fixed | Exception Handling: Allow anonymous typed handlers |
| [BOO-878](issues/BOO-0878.md) | :white_check_mark: Fixed | Exception Handling: Verify that all catch blocks can be reached |
| [BOO-879](issues/BOO-0879.md) | :white_check_mark: Fixed | Exception Handling: Allow for exception filters |
| [BOO-880](issues/BOO-0880.md) | :white_check_mark: Fixed | Exception Handling: Allow for exception fault handlers |
| [BOO-881](issues/BOO-0881.md) | :white_check_mark: Fixed | compiler doesn't check for duplicate parameter names in constructor definitions |
| [BOO-882](issues/BOO-0882.md) | :white_check_mark: Fixed | compiler error on generic types containing multiple generic indexers |
| [BOO-883](issues/BOO-0883.md) | :white_check_mark: Fixed | Internal error using regular expression in generator |
| [BOO-884](issues/BOO-0884.md) | :white_check_mark: Fixed | compiler should prefer data preserving overloads |
| [BOO-885](issues/BOO-0885.md) | :white_check_mark: Fixed | parser doesnt allow complex expressions inside closures |
| [BOO-886](issues/BOO-0886.md) | :large_blue_circle: Open | Bad error message when using variable number of arguments |
| [BOO-887](issues/BOO-0887.md) | :white_check_mark: Fixed | Wrong stack trace information for exception during assignment inside generator method |
| [BOO-888](issues/BOO-0888.md) | :white_check_mark: Fixed | Delay Sign parameter is ignored |
| [BOO-889](issues/BOO-0889.md) | :white_check_mark: Fixed | BooPrinterVistor makes ugly elif chains |
| [BOO-890](issues/BOO-0890.md) | :white_check_mark: Fixed | BooPrinterVistor doesn't know about WhiteSpaceAgnostic mode when used as part of the PrintBoo compiler step |
| [BOO-891](issues/BOO-0891.md) | :white_check_mark: Fixed | Boo.NAnt.Tasks is using an obsolete method (Assembly.LoadWithPartialName) |
| [BOO-892](issues/BOO-0892.md) | :white_check_mark: Fixed | Test Cases use obsolete interfaces and throw warnings during compilation |
| [BOO-893](issues/BOO-0893.md) | :white_check_mark: Fixed | QuackInvoke intercepts calls to super() in class CTOR |
| [BOO-894](issues/BOO-0894.md) | :white_check_mark: Fixed | Type inference failure for property used in object initializer |
| [BOO-895](issues/BOO-0895.md) | :white_check_mark: Fixed | [MetaProgramming] splicing for member references |
| [BOO-896](issues/BOO-0896.md) | :white_check_mark: Fixed | [MetaProgramming] splicing for class and field names |
| [BOO-897](issues/BOO-0897.md) | :white_check_mark: Fixed | [MetaProgramming] splicing for method names |
| [BOO-898](issues/BOO-0898.md) | :white_check_mark: Fixed | [MetaProgramming] Splicing operator is not recognized inside string expression interpolation |
| [BOO-899](issues/BOO-0899.md) | :white_check_mark: Fixed | bool equality comparisons are emitting unnecessary RuntimeServices.EqualityOperator calls |
| [BOO-900](issues/BOO-0900.md) | :white_check_mark: Fixed | unreserve 'otherwise' keyword so it can be used by the 'match' macro |
| [BOO-901](issues/BOO-0901.md) | :white_check_mark: Fixed | unreserve 'given' and 'when' keywords so they can be implemented as macros |
| [BOO-902](issues/BOO-0902.md) | :white_check_mark: Fixed | Resolve extensions methods against implicit 'self' target |
| [BOO-903](issues/BOO-0903.md) | :no_entry_sign: Won't Fix | Allow 'of' to be omitted in type references when [] are used |
| [BOO-904](issues/BOO-0904.md) | :white_check_mark: Fixed | [MetaProgramming] ability to splice expressions wherever type reference are expected |
| [BOO-905](issues/BOO-0905.md) | :white_check_mark: Fixed | [MetaProgramming] ability to use type definition references wherever type references are expected |
| [BOO-906](issues/BOO-0906.md) | :white_check_mark: Fixed | Internal error with GetType() inside internal generic type that inherits from internal generic type |
| [BOO-907](issues/BOO-0907.md) | :white_check_mark: Fixed | Strings raised as exceptions should not raise ApplicationException |
| [BOO-908](issues/BOO-0908.md) | :white_check_mark: Fixed | SingletonAttribute doesn't protect against deserialization instatiating multiple singletons |
| [BOO-909](issues/BOO-0909.md) | :large_blue_circle: Open | Compiler fails to recognize event definition in a class when the Interface for the class is defined in another assembly |
| [BOO-910](issues/BOO-0910.md) | :white_check_mark: Fixed | Boo doesn't catch non-CLS compliant exceptions at runtime |
| [BOO-911](issues/BOO-0911.md) | :white_check_mark: Fixed | [MetaProgramming] name splicing for interfaces and interface methods |
| [BOO-912](issues/BOO-0912.md) | :large_blue_circle: Open | Make CompilerPipelines composable |
| [BOO-913](issues/BOO-0913.md) | :white_check_mark: Fixed | Compiler searches default imports first for import statements rather than global namespace |
| [BOO-914](issues/BOO-0914.md) | :white_check_mark: Fixed | Extract Macros and Attributes from the Boo.Lang.Compiler into Boo.Lang.Extensions |
| [BOO-915](issues/BOO-0915.md) | :white_check_mark: Fixed | Boo Compiler is not flagging virtual constructors as invalid before attempting emit. |
| [BOO-916](issues/BOO-0916.md) | :white_check_mark: Fixed | Types marked 'static' should warn about redundant use of static on types marked static; disallow 'abstract final' combination |
| [BOO-917](issues/BOO-0917.md) | :white_check_mark: Fixed | Interfaces can be marked final. |
| [BOO-918](issues/BOO-0918.md) | :white_check_mark: Fixed | Types marked as 'static' should automatically mark all members as static and make the type 'abstract final' |
| [BOO-919](issues/BOO-0919.md) | :white_check_mark: Fixed | Compiler doesn't notice inherited indexers on external interfaces |
| [BOO-920](issues/BOO-0920.md) | :white_check_mark: Fixed | len returns 0 for objects that have no concept of length. it should throw ArgumentException |
| [BOO-921](issues/BOO-0921.md) | :large_blue_circle: Open | remove superfluous brackets from if .. else .. construction |
| [BOO-922](issues/BOO-0922.md) | :large_blue_circle: Open | InheritBaseConstructors ast attribute |
| [BOO-923](issues/BOO-0923.md) | :large_blue_circle: Open | error when parsing a floating point literal with no decimal point |
| [BOO-924](issues/BOO-0924.md) | :white_check_mark: Fixed | [MetaProgramming] Parameter splicing |
| [BOO-925](issues/BOO-0925.md) | :white_check_mark: Fixed | Ability to use macros defined in the same compilation unit |
| [BOO-926](issues/BOO-0926.md) | :white_check_mark: Fixed | nested functions |
| [BOO-927](issues/BOO-0927.md) | :white_check_mark: Fixed | Method OverLoad Resolution With Predicates |
| [BOO-928](issues/BOO-0928.md) | :white_check_mark: Fixed | Ambiguous reference for types with same name and different number of generic arguments |
| [BOO-929](issues/BOO-0929.md) | :large_blue_circle: Open | code literal should be inferred to be a block |
| [BOO-930](issues/BOO-0930.md) | :large_blue_circle: Open | *.csproj and *.sln files should be part of the source distro |
| [BOO-931](issues/BOO-0931.md) | :white_check_mark: Fixed | Attributes like Property , Getter , Setter working no more! |
| [BOO-932](issues/BOO-0932.md) | :large_blue_circle: Open | Macro Operators |
| [BOO-933](issues/BOO-0933.md) | :large_blue_circle: Open | Greedy ExpandVarArgsInvocation |
| [BOO-934](issues/BOO-0934.md) | :white_check_mark: Fixed | property name splicing |
| [BOO-935](issues/BOO-0935.md) | :construction: In Progress | Declaring constraints on generic type parameters |
| [BOO-936](issues/BOO-0936.md) | :grey_question: Cannot Reproduce | Internal compiler error when Boo classes used as Generic Types [Possible Regression from 0.7.8] |
| [BOO-937](issues/BOO-0937.md) | :white_check_mark: Fixed | Support CLR 3.5 Extension Methods |
| [BOO-938](issues/BOO-0938.md) | :large_blue_circle: Open | Support for CLR 3.5 Extensions for duck types |
| [BOO-939](issues/BOO-0939.md) | :large_blue_circle: Open | Internal ObsoleteAttribute ignored |
| [BOO-940](issues/BOO-0940.md) | :white_check_mark: Fixed | WARNING: Private member X is never used. |
| [BOO-941](issues/BOO-0941.md) | :large_blue_circle: Open | Compiler's generic constraint check is not tight enough [Go - Branch] |
| [BOO-942](issues/BOO-0942.md) | :link: Duplicate | Code that generates invalid IL |
| [BOO-943](issues/BOO-0943.md) | :white_check_mark: Fixed | Implicit downcast in strict mode |
| [BOO-944](issues/BOO-0944.md) | :large_blue_circle: Open | Using [property] and named arguments in an AstAttribute crashes compiler |
| [BOO-945](issues/BOO-0945.md) | :large_blue_circle: Open | Remove Mono hack on GenericGeneratorEnumerator (BOO-796) |
| [BOO-946](issues/BOO-0946.md) | :white_check_mark: Fixed | Warning: namespace is never used |
| [BOO-947](issues/BOO-0947.md) | :large_blue_circle: Open | generic callable generates bad IL when generic parameter is itself a parameter. |
| [BOO-948](issues/BOO-0948.md) | :white_check_mark: Fixed | Compiler crashes when a pinvoke with no return type declared is never used |
| [BOO-949](issues/BOO-0949.md) | :white_check_mark: Fixed | Cannot declare generic method overload with same signature as non-generic overload |
| [BOO-950](issues/BOO-0950.md) | :white_check_mark: Fixed | Automatic stub creation for non-implemented properties too. |
| [BOO-951](issues/BOO-0951.md) | :white_check_mark: Fixed | Add introspection feature to IQuackFu |
| [BOO-952](issues/BOO-0952.md) | :white_check_mark: Fixed | Remove all handlers attached to an event with 'SomeEvent = null' |
| [BOO-953](issues/BOO-0953.md) | :large_blue_circle: Open | extensible interpreter architecture |
| [BOO-954](issues/BOO-0954.md) | :large_blue_circle: Open | When building some .dll don't have a version number (Boo.Lang.Extensions.dll, Boo.Lang.Interpreter.dll, etc) |
| [BOO-955](issues/BOO-0955.md) | :white_check_mark: Fixed | Implementing an interface method with incompatible method signature doesn't ring any bell |
| [BOO-956](issues/BOO-0956.md) | :large_blue_circle: Open | string.Concat-based string interpolation |
| [BOO-957](issues/BOO-0957.md) | :large_blue_circle: Open | CheckedQuackFu - compile-time checking for quack types |
| [BOO-958](issues/BOO-0958.md) | :white_check_mark: Fixed | ref keyword for generic parameters causes compiler error |
| [BOO-959](issues/BOO-0959.md) | :white_check_mark: Fixed | Suggest most similar sounding member when member not found error is issued. |
| [BOO-960](issues/BOO-0960.md) | :white_check_mark: Fixed | Compiler cannot disambiguate between regular and generically mapped callables |
| [BOO-961](issues/BOO-0961.md) | :white_check_mark: Fixed | Shorthand syntax for IEnumerable of T |
| [BOO-962](issues/BOO-0962.md) | :white_check_mark: Fixed | Use ValueType Iterators |
| [BOO-963](issues/BOO-0963.md) | :large_blue_circle: Open | Members declared with anonymous types cannot be implemented or overriden in separate assembly |
| [BOO-964](issues/BOO-0964.md) | :grey_question: Cannot Reproduce | shared method bodies |
| [BOO-965](issues/BOO-0965.md) | :large_blue_circle: Open | Explicit interface implementation of generic interfaces |
| [BOO-966](issues/BOO-0966.md) | :large_blue_circle: Open | x = (.. if .. else ..) doesn't verify type's accordance |
| [BOO-967](issues/BOO-0967.md) | :large_blue_circle: Open | There is no value safety in duck typing |
| [BOO-968](issues/BOO-0968.md) | :white_check_mark: Fixed | Allow for the use of a custom exception message for the required attribute |
| [BOO-969](issues/BOO-0969.md) | :white_check_mark: Fixed | Cycle over attribute application and macro expansion until all are applied and expanded (within a fixed limit of iterations) |
| [BOO-970](issues/BOO-0970.md) | :large_blue_circle: Open | interpreter is unable to calculate a logic expression. |
| [BOO-971](issues/BOO-0971.md) | :white_check_mark: Fixed | AttributeUsageAttribute.ReturnValue is not checked properly |
| [BOO-972](issues/BOO-0972.md) | :white_check_mark: Fixed | Compiler wont accept Nullable[of date] |
| [BOO-973](issues/BOO-0973.md) | :white_check_mark: Fixed | compiler error when attaching to an event on a locally defined generic or on a generic using a locally defined type parameter |
| [BOO-974](issues/BOO-0974.md) | :white_check_mark: Fixed | Compiler crashes on same-class instance generic method invocation when self keyword is not used and a non-generic compatible overload exists. |
| [BOO-975](issues/BOO-0975.md) | :white_check_mark: Fixed | BadImageFormatException - compiler not checking presence of type parameters when constructing generic types |
| [BOO-976](issues/BOO-0976.md) | :large_blue_circle: Open | Boo compiler incorrectly handles generic type parameter constraints involving the constrained type parameter |
| [BOO-977](issues/BOO-0977.md) | :white_check_mark: Fixed | compiler error on referencing inherited member of generic subclass instance |
| [BOO-978](issues/BOO-0978.md) | :white_check_mark: Fixed | CodeDom support for partial classes |
| [BOO-979](issues/BOO-0979.md) | :white_check_mark: Fixed | compiler error on external generic methods called with internal arguments |
| [BOO-980](issues/BOO-0980.md) | :white_check_mark: Fixed | performance problem in MetadataUtil.IsAttributeDefined |
| [BOO-981](issues/BOO-0981.md) | :construction: In Progress | The Coordinated movement to reduce the number of warnings in our default build |
| [BOO-982](issues/BOO-0982.md) | :white_check_mark: Fixed | IQuackFu implementing object incorrectly intercepts constructor chaining calls |
| [BOO-983](issues/BOO-0983.md) | :white_check_mark: Fixed | Compiation of types inheriting from constructed generic types is order dependent |
| [BOO-984](issues/BOO-0984.md) | :large_blue_circle: Open | nested function can't call itself |
| [BOO-985](issues/BOO-0985.md) | :white_check_mark: Fixed | Allow arithmetic operations with nullables |
| [BOO-986](issues/BOO-0986.md) | :white_check_mark: Fixed | DefaultAttribute doesn't work on typeless parameters |
| [BOO-987](issues/BOO-0987.md) | :white_check_mark: Fixed | Allow arbitrary Boo scripts to be run from within an MSBuild target |
| [BOO-988](issues/BOO-0988.md) | :white_check_mark: Fixed | optional 'else' block for 'for' and 'while' loops |
| [BOO-989](issues/BOO-0989.md) | :white_check_mark: Fixed | Possibly suggest alternative when a function marked with 'override' doesn't override anything |
| [BOO-990](issues/BOO-0990.md) | :white_check_mark: Fixed | Allow Test cases to be ignored when building testcase tree |
| [BOO-991](issues/BOO-0991.md) | :white_check_mark: Fixed | Implement a loop feature that executes only if the loop condition fails on its first execution |
| [BOO-992](issues/BOO-0992.md) | :white_check_mark: Fixed | Compiler cannot disambiguate between non-generic and generic with the same name (including generic with a different number of generic parameters) |
| [BOO-993](issues/BOO-0993.md) | :white_check_mark: Fixed | Unable to invoke clr extension method through its static signature since rev. 2861 |
| [BOO-994](issues/BOO-0994.md) | :white_check_mark: Fixed | Generic extension methods |
| [BOO-995](issues/BOO-0995.md) | :arrows_counterclockwise: Reopened | Add the "or" keyword semantic for for/while loops |
| [BOO-996](issues/BOO-0996.md) | :white_check_mark: Fixed | Modify the for/while "else" semantic to use a new keyword: "then" |
| [BOO-997](issues/BOO-0997.md) | :grey_question: Cannot Reproduce | Two BeginInvoke on 'functions as objects' with different argument types makes the compiler crash |
| [BOO-998](issues/BOO-0998.md) | :white_check_mark: Fixed | compiler error in generator with try block |
| [BOO-999](issues/BOO-0999.md) | :white_check_mark: Fixed | Overload resolution inconsistency on duck vs. non-duck |
| [BOO-1000](issues/BOO-1000.md) | :construction: In Progress | Non-null type T! |
| [BOO-1001](issues/BOO-1001.md) | :large_blue_circle: Open | Merge code from CRS to RuntimeServices |
| [BOO-1002](issues/BOO-1002.md) | :white_check_mark: Fixed | booish(2) instability |
| [BOO-1003](issues/BOO-1003.md) | :large_blue_circle: Open | Support CoClassAttribute |
| [BOO-1004](issues/BOO-1004.md) | :construction: In Progress | Support friend assemblies (InternalsVisibleTo attribute) |
| [BOO-1005](issues/BOO-1005.md) | :white_check_mark: Fixed | no support for generic methods in interface declarations |
| [BOO-1006](issues/BOO-1006.md) | :white_check_mark: Fixed | String interpolation formatting |
| [BOO-1007](issues/BOO-1007.md) | :grey_question: Cannot Reproduce | compile error in 0.8.1 on Mac OS X |
| [BOO-1008](issues/BOO-1008.md) | :white_check_mark: Fixed | Compiler crash when a class defines a method and there is an explicit interface implementation of same signature |
| [BOO-1009](issues/BOO-1009.md) | :white_check_mark: Fixed | Explicit interface property implementation uses 'implicit' implementation when there is one. |
| [BOO-1010](issues/BOO-1010.md) | :large_blue_circle: Open | Fix Command-Line Argument Parsing Issue For Target Boo.NAnt.Tasks |
| [BOO-1011](issues/BOO-1011.md) | :large_blue_circle: Open | Smart bitfield enum |
| [BOO-1012](issues/BOO-1012.md) | :white_check_mark: Fixed | Cannot build boo msbuild task on .NET 2.0 since rev. 2910 |
| [BOO-1013](issues/BOO-1013.md) | :white_check_mark: Fixed | A stub is always created when a class implements an abstract generic method with at least one generic argument |
| [BOO-1014](issues/BOO-1014.md) | :large_blue_circle: Open | compiler error when slicing ambiguous reference |
| [BOO-1015](issues/BOO-1015.md) | :construction: In Progress | Hiding/shadowing an inherited field does not warn |
| [BOO-1016](issues/BOO-1016.md) | :white_check_mark: Fixed | Conflict between generic and non-generic methods overloads when return type is generic parameter |
| [BOO-1017](issues/BOO-1017.md) | :white_check_mark: Fixed | Anonymous blocks and pass doesn't mix |
| [BOO-1018](issues/BOO-1018.md) | :white_check_mark: Fixed | Statement modifiers and DSL methods |
| [BOO-1019](issues/BOO-1019.md) | :white_check_mark: Fixed | A class with a static constructor emits 'beforeFieldInit' |
| [BOO-1020](issues/BOO-1020.md) | :white_check_mark: Fixed | Inplace-XOR operator crashes compiler |
| [BOO-1021](issues/BOO-1021.md) | :white_check_mark: Fixed | Automatically set protected member in a final/sealed type as private |
| [BOO-1022](issues/BOO-1022.md) | :large_blue_circle: Open | module initializer as a static constructor |
| [BOO-1023](issues/BOO-1023.md) | :large_blue_circle: Open | Explicit Properties and Methods Can Not Have Different Type Than Implicit Properties and Methods |
| [BOO-1024](issues/BOO-1024.md) | :white_check_mark: Fixed | Calling method with nullable parameter generates invalid IL |
| [BOO-1025](issues/BOO-1025.md) | :large_blue_circle: Open | Suggestions for BCE0005 Unknown identifier |
| [BOO-1026](issues/BOO-1026.md) | :large_blue_circle: Open | Generic return type incompatibility |
| [BOO-1027](issues/BOO-1027.md) | :white_check_mark: Fixed | Cannot override methods with ref parameters to non-primitive types |
| [BOO-1028](issues/BOO-1028.md) | :large_blue_circle: Open | composition AST attribute |
| [BOO-1029](issues/BOO-1029.md) | :construction: In Progress | prettier error messages with nullable and enumerable types |
| [BOO-1030](issues/BOO-1030.md) | :white_check_mark: Fixed | smart indentation in booish |
| [BOO-1031](issues/BOO-1031.md) | :white_check_mark: Fixed | Conflict when an explicitely implemented method has a sibling overload with incompatible signature |
| [BOO-1032](issues/BOO-1032.md) | :white_check_mark: Fixed | Ambiguous reference when trying to access a non-explicit member which also has an explicit implementation overload |
| [BOO-1033](issues/BOO-1033.md) | :white_check_mark: Fixed | AmbiguousMatchException on overloaded indexer |
| [BOO-1034](issues/BOO-1034.md) | :white_check_mark: Fixed | compiler error referencing base class members of a generic subclass of a generic class |
| [BOO-1035](issues/BOO-1035.md) | :white_check_mark: Fixed | empty strings are considered true in a boolean context |
| [BOO-1036](issues/BOO-1036.md) | :large_blue_circle: Open | named properties in constructor ambiguity |
| [BOO-1037](issues/BOO-1037.md) | :large_blue_circle: Open | shorthand loops |
| [BOO-1038](issues/BOO-1038.md) | :no_entry_sign: Won't Fix | Docstrings do not work on interface method declarations with 'pass' |
| [BOO-1039](issues/BOO-1039.md) | :white_check_mark: Fixed | Ability to suppress warnings at the API level |
| [BOO-1040](issues/BOO-1040.md) | :white_check_mark: Fixed | Calling a constructor overload calls $initializer$ again |
| [BOO-1041](issues/BOO-1041.md) | :construction: In Progress | Implement 'complex slicing' on any enumerable |
| [BOO-1042](issues/BOO-1042.md) | :white_check_mark: Fixed | Invalid IL generated when ctor calls an instance method before self() or super() |
| [BOO-1043](issues/BOO-1043.md) | :large_blue_circle: Open | [resetable] AST attribute on generators |
| [BOO-1044](issues/BOO-1044.md) | :link: Duplicate | nullables explode at runtime but not compile time |
| [BOO-1045](issues/BOO-1045.md) | :white_check_mark: Fixed | Warn when object.Finalize() is overriden, suggest using destructor syntax instead |
| [BOO-1046](issues/BOO-1046.md) | :arrows_counterclockwise: Reopened | Strange character appear if file encoding is not utf8 |
| [BOO-1047](issues/BOO-1047.md) | :white_check_mark: Fixed | Internal compiler error when invoking external generic method where type inference violates generic constraints |
| [BOO-1048](issues/BOO-1048.md) | :large_blue_circle: Open | optimize flag for booc |
| [BOO-1049](issues/BOO-1049.md) | :white_check_mark: Fixed | meta methods should be able to return null (meaning "remove the statement") |
| [BOO-1050](issues/BOO-1050.md) | :white_check_mark: Fixed | CompilerContext.Current |
| [BOO-1051](issues/BOO-1051.md) | :white_check_mark: Fixed | Conflict between explicitly implemented property and generic property |
| [BOO-1052](issues/BOO-1052.md) | :white_check_mark: Fixed | Internal compiler error when a class has a non-event member with the same name as an abstract or interface event |
| [BOO-1053](issues/BOO-1053.md) | :large_blue_circle: Open | Refactor ProcessInheritedAbstractMembers step |
| [BOO-1054](issues/BOO-1054.md) | :white_check_mark: Fixed | No BCW0004 warning "rhs of `is` is a type reference" when type is generic |
| [BOO-1055](issues/BOO-1055.md) | :large_blue_circle: Open | cannot define non-explicit property when an explicit one with different signature exists |
| [BOO-1056](issues/BOO-1056.md) | :large_blue_circle: Open | Class variable initializers are run after base constructor(s) |
| [BOO-1059](issues/BOO-1059.md) | :white_check_mark: Fixed | Compile error when classes with destructors have nested types |
| [BOO-1060](issues/BOO-1060.md) | :link: Duplicate | Static constructors should be emitted as private. |
| [BOO-1061](issues/BOO-1061.md) | :large_blue_circle: Open | Use of IEquatable[of T] with value types can trigger NullReferenceExceptions |
| [BOO-1063](issues/BOO-1063.md) | :white_check_mark: Fixed | macros anywhere in a module |
| [BOO-1064](issues/BOO-1064.md) | :arrows_counterclockwise: Reopened | Overriden explicit interface implementation crashes compiler |
| [BOO-1065](issues/BOO-1065.md) | :white_check_mark: Fixed | Duplicate explicit interfaces cause emit error |
| [BOO-1066](issues/BOO-1066.md) | :large_blue_circle: Open | operator precedence violation: - x**2 is considered as (- x)**2 |
| [BOO-1067](issues/BOO-1067.md) | :large_blue_circle: Open | Allow Compilation Process to Handle .resources Files With Stream-Based Resources |
| [BOO-1068](issues/BOO-1068.md) | :white_check_mark: Fixed | statement modifiers are eaten by code literals |
| [BOO-1069](issues/BOO-1069.md) | :white_check_mark: Fixed | Modulus doesn't support InPlace operation |
