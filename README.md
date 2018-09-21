# cpp-review-checklist-TCS-internal
Checklist of CPP code before submission
The following check list is to be used in the assessment of C++ source code during a peer
review. Items which represent the code being reviewed should be checked.
1. General Programming Standards and Guidelines
Refer to the OHD General Programming Standards and Guidelines Peer Review
Checklist to assess the adherence to the OHD General Programming Standards and
Guidelines.
2. C++ Programming Standards
 Readability and Maintainability
 Consistent indentation (3 or 4 spaces)
 Consistent use of braces
 No tabs used
 File Names
 Header files and namespace files use suffixes: .h, .H, .hh, .hpp, or .hxx
 Source files use suffixes: .C, .cc, .cpp, or .cxx
 UpperMixedCase is used for class or namespace file names
 lowerMixedCase is used for function file names
 File Organization
 Each file contains only one class declaration or definition except static classes
 File includes a brief description of the file after the documentation block
 The content of the file is in the following order:
1. The preprocessor directives to prevent multiple inclusions in header files.
2. The Documentation block described in the "OHD General Software
Development Standards and Guidelines"
3. A brief description of the file
4. Include files
5. #defines and Macros
6. The ‘use’ directives in the source f
7. Class or function declaration or definition
 Include Files
 C++ standard library headers that have no extension are used
 New prefix c is used instead of the old extension .h for C standard header files
 The < > pair for library and system headers is used
 The " " pair for non-system (user defined) headers is used
 No absolute or relative paths to point to the header files are use
 The system header files first in alphabetical order followed by the non-system
 include files (including COTS includes) also in alphabetical order
 Comments
 The JavaDoc convention format is used for the documentation comment
 The C++ comment "//" style or the C style (/* ... */) is used for inline comments
 Naming Schemes
 namespace, class, struct, template argument, and parameter names use uppercase
letters as word separators with the first character capitalized
 Macro and #defined constant, enum, union, class static data member, and global variable
names are all capitalized with underscore as separators
 Class methods and variable names use uppercase letters as word separators with the first
character is not capitalized
 Private class data member names are prepended with the underscore, the rest is the same
as method names
 static const data members are all uppercase
 typedef names reflect the style appropriate to the underlying type
 Class, struct, variable, and method names that differ by case only are not used
 Class Design
 Class members are declared in this order: public members, protected members, private
members
 Data members are properly protected (declared as private or protected)
 Classes (except functors and static classes) implement a default constructor, a virtual
destructor, a copy constructor, and an overloaded assignment operator
 Static classes declare a private default constructor to prevent instantiation 
 Safety and Performance
 Type conversions have been done explicitly. The C++ set of casting operators
static_cast, reinterpret_cast, const_cast and dynamic_cast have been used
instead of C-style casting
 Global variables are not used except in rare cases and when used include an inline
comment describing the reason for use.
 Dynamically allocated memory is deallocated when no longer needed
 There is no dangling pointers. Pointers ar
 Performance
 inline functions are used instead of Macros
 The prefix form (++i or --i) is used instead of postfix form (i++ or i--)
 Pointer arithmetic has been avoided
 Repetitive computations are reduced by only doing them once and saving the
result in a temporary variable for future access
C++ Code Checklist
COMPLETE:
 Verify that the code covers all the design.
INCLUDES:
 Verify that ‘includes’ are complete.
INITIALIZATION:
 Check variable and parameter initialization:
 At program initiation.
 At start of every loop.
 At function/procedure entry.
CALLS:
 Check function call formats:
 Pointers
 Parameters
 Use of "&".
NAMES:
 Check name spelling and use:
 Is it consistent ?
 Is it within the declared scope ?
 Do all structures and classes use “.” Reference ?
STRINGS:
 Check that all strings are:
 Identified by pointers,
 Terminated in NULL
 POINTERS:
 Pointers are initialized NULL,
 Pointers are deleted only after new,
 New pointers always deleted after use.
OUTPUT FORMAT:
 Line stepping is proper.
 Spacing is proper.
PAIRS:
 Ensure the { } are proper and matched.
LOGIC OPERATORS:
 Verify that the proper use of ==, =, //, and so on.
 Check every logic function for proper ( }.
SUNTAX:
 Check every line of code for:
 Instruction syntax
 Proper punctuation.
STANDARDS:
 Ensure the code conforms to the project’s coding standards.
FILE OPEN AND CLOSE:
 Verify that all files are:
 Properly declared
 Opened
 Closed.
