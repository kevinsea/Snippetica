﻿# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

### Added

- Add snippet for 'while not' (`wx`) ([#54](https://github.com/josefpihrt/roslynator/pull/54)).

## [1.0.0] - 2022-10-17

### Added

- Add CODEOWNERS file ([#21](https://github.com/josefpihrt/snippetica/pull/21)).
- Add support for Visual Studio 2022 ([#22](https://github.com/josefpihrt/snippetica/pull/22)).
- Add snippet for `KeyValuePair.Create` (`kvpc`) ([#24](https://github.com/josefpihrt/snippetica/pull/24)), ([#26](https://github.com/josefpihrt/snippetica/pull/26)).
- Add snippet for 'using declaration' (`uv`) ([#27](https://github.com/josefpihrt/snippetica/pull/27)).
- Add snippet for 'switch expression' (`swe`) ([#34](https://github.com/josefpihrt/roslynator/pull/34)).

### Changed

- Rename default branch to `main`.
- Format changelog according to 'Keep a Changelog' ([#17](https://github.com/josefpihrt/snippetica/pull/17)).
- Update projects to .NET 4.8 ([#18](https://github.com/josefpihrt/snippetica/pull/18)).
- Move solution file to `src` ([#19](https://github.com/josefpihrt/snippetica/pull/19)).
- Replace ruleset file with EditorConfig ([#20](https://github.com/josefpihrt/snippetica/pull/20)).
- Migrate projects to a new csproj format ([#23](https://github.com/josefpihrt/snippetica/pull/23)).
- Add `Directory.Build.props` ([#23](https://github.com/josefpihrt/snippetica/pull/23)).
- Simplify snippet 'using statement' (`u`) ([#27](https://github.com/josefpihrt/snippetica/pull/27)).
- Use pattern matching to check for null ([#29](https://github.com/josefpihrt/snippetica/pull/29)).
- Change shortcut for 'interface declaration' from `ie` to `i` ([#30](https://github.com/josefpihrt/snippetica/pull/30)), ([#48](https://github.com/josefpihrt/snippetica/pull/48)).
- Change shortcut for 'while' from `we` to `w` ([#33](https://github.com/josefpihrt/snippetica/pull/33)), ([#53](https://github.com/josefpihrt/snippetica/pull/53)).
- Change shortcut for 'switch statement' from `sh` to `sw` ([#35](https://github.com/josefpihrt/roslynator/pull/35)), ([#38](https://github.com/josefpihrt/roslynator/pull/38)).
- Change shortcut for 'enum' from `em` to `en` ([#31](https://github.com/josefpihrt/roslynator/pull/31)).
- Change shortcut for 'record declaration' from `rd` to `re` ([#39](https://github.com/josefpihrt/snippetica/pull/39)).
- Change shortcut for 'indexer' from `ir` to `in` ([#40](https://github.com/josefpihrt/snippetica/pull/40)).
- Change shortcut for 'event declaration' from `et` to `ev` ([#42](https://github.com/josefpihrt/roslynator/pull/42)).
- Change shortcut for 'throw statement' from `tw` to `th` ([#41](https://github.com/josefpihrt/roslynator/pull/41)).
- Change shortcut for constructor from `cr` to `co` ([#43](https://github.com/josefpihrt/snippetica/pull/43)).
- Change shortcut for ternary conditional operator from `co` to `cop` ([#43](https://github.com/josefpihrt/snippetica/pull/43)).
- Change shortcut for 'module declaration' from `me` to `mo` ([#44](https://github.com/josefpihrt/snippetica/pull/44)).
- Change shortcut for 'destructor declaration' from `dr` to `de` ([#45](https://github.com/josefpihrt/snippetica/pull/45)).
- Change shortcut for 'namespace declaration' from `ns` to `na` ([#47](https://github.com/josefpihrt/snippetica/pull/47)).
- [C++] Change shortcut for 'cast' from `ct` to `ca` ([#50](https://github.com/josefpihrt/snippetica/pull/50)).
- [C++] Change shortcut for 'inline' from `il` to `i` ([#51](https://github.com/josefpihrt/snippetica/pull/51)).
- [C++] Change shortcut for 'do-while' from `dw` to `do` ([#52](https://github.com/josefpihrt/snippetica/pull/52)).

### Removed

- Remove snippet for type parameter (`g`) ([#28](https://github.com/josefpihrt/snippetica/pull/28)).
- Remove snippets where return type is either Int64 or DateTime ([#36](https://github.com/josefpihrt/snippetica/pull/36)).

-----
<!-- Content below does not adhere to 'Keep a Changelog' format -->

## 0.9.2 (2021-11-14)

### New Snippets for C#

* Lambda expression without parameters (l0)
* DateTimeOffset (dto)
* KeyValuePair (kvp)
* Record (rd)
* Record struct (rdst)
* Readonly record struct (rrdst)
* Attribute a
  * AttributeUsage (au)
  * Conditional (c)
  * DebuggerDisplay (dd)
  * DebuggerStepThrough (dst)
  * DefaultValue (dv)
  * Description (d)
  * Flags (f)
  * Obsolete (o)
  * Required (r)
  * TypeConverter (tc)

## 0.9.1 (2019-04-14)

* Put back snippets that were accidentally removed in 0.9.0 (ifxtp, ifx, ifxn, xn, xsne, xsnw).

### Snippets for C# and VB

* Change shortcut ge to j
* Change shortcut gc to j
* Change shortcut vc to vn
* Change shortcut vcx to vnx

## 0.9.0 (2019-03-21)

### Snippets for C# and VB

* Change shortcut ge to j
* Change shortcut gc to j
* Change shortcut vc to vn
* Change shortcut vcx to vnx

## 0.8.0 (2018-04-04)

### New Snippets for C# and VB

* Read-only indexer (rir)
* ThrowNewObjectDisposedException (twn ode)

### New Snippets for C#

* Read-only struct (rst)

## 0.7.0 (2017-12-13)

* Rewrite C++ snippets
* Change shortcut for '...WithInitializer' snippets from '_' to 'x' (C# and VB)
* Remove '...WithArguments' snippets and '...WithParameters' snippets (C# and VB)

## 0.6.0 (2017-09-24)

### New Shortcuts

Shortcut | Description | Comment
-------- | ----------- | -------
x|logical not operator|prefix

### New Snippets

Language | Shortcut | Title
-------- | -------- | -----
C\+\+|eif|else\-if
C\#|coxn|conditional operator \(not equal to null\)
C\#|con|conditional operator \(equal to null\)
C\#|doxn|do\-while not null
C\#|don|do\-while null
C\#|l2|lambda expression with 2 parameters
C\#|wexn|while not null
C\#|wen|while null
VB|l2|lambda expression with 2 parameters
VB|wexn|while not null
VB|wen|while null

## 0.5.2 (2017-05-28)

### New Snippets

Language | Shortcut | Title
-------- | -------- | -----
C\#|iftp|if TryParse
C\#|ifftp|if not TryParse
C\#|u|StreamReader variable
C\#|u|StreamWriter variable
C\#|u|StringReader variable
C\#|u|StringWriter variable
C\#|u|XmlReader variable
C\#|u|XmlWriter variable
C\#|us|using static directive
VB|iftp|if TryParse
VB|ifftp|if not TryParse
VB|u|StreamReader variable
VB|u|StreamWriter variable
VB|u|StringReader variable
VB|u|StringWriter variable
VB|u|XmlReader variable
VB|u|XmlWriter variable

## 0.5.1 (2017-03-09)

### New Snippets

* 'virtual/Overridable' snippets

## 0.5.0 (2016-12-30)

### New Snippets

Language | Shortcut | Title
-------- | -------- | -----
C\#|u|IEnumerator\<T\> variable
C\#|u|using variable
C\#|vb|Boolean variable
C\#|vi|Int32 variable
C\#|vs|String variable
C\#|vt|variable declaration with explicit cast operator
VB|u|IEnumerator\(Of T\) variable
VB|vb|Boolean variable
VB|vi|Int32 variable
VB|vs|String variable
VB|vt|variable with DirectCast

## 0.1.0 (2016-10-16)

* Initial release
