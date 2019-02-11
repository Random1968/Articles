---
Title: Open Source Libraries
Author: Ivan Nekrasov
Center: C
Section: Standard
Tags: Open Source, License, GPL
---

#**Open Source Libraries**

## Introduction

If you are using open source libraries in your project, it is important to check the licenses associated with them.

You can find more information about licenses in the [**Resources**](#resources) section of the present guide.

>**Important**: Before an open source library is used in a project, it needs to be explicitly approved from both a technical and a legal perspective.

## Licenses Types

To save your time and improve the chances for approval to use a particular library, please check the license of the library. For this purpose, use this section as guidance. 

> **Important**: It is incorrect to assume that any source code without a license is in the pubic domain. On the contrary, it has an implicit copyright and cannot be used without the author's permission.

Anything we need to modify should have the following licenses: 
- [Apache v2][1]
- [MIT][2]
- [BSD][3]

Anything else that we wish to leverage should have the following licenses: 
- [LGPL][4]
- [GPL][5]
- [GPLv2][6]

Specifically, we want to avoid the following types of licenses:
- [AGPL][7] 

> **Important**: Even if a library has a good license such as MIT, you **must** anyway obtain explicit approval to use it as described in the process below.

## Approval Process

1. When you need to use a 3rd party library, try to find the library in the list of [open source libraries list](https://www.quora.com/What-is-an-open-source-library) and, if it is there and is approved, you can use it. If it is not in the list or has not been approved, you should proceed to the next step.

2. Send a request to the lead/architect in your team for approval to use the library indicating the following details:
 - the name of the library and a link to its code;
 - the type of license and a link to the license text;
 - justification;
 - state whether you plan to modify the library or not;
 - the impact date.
    
3. The lead/architect may reject your request for permission to use the library if a similar library is already in use in the project or for other reasons.

4. If the lead/architect believes that using the library is justified, they:
 - send a request to the [OpenSourceRequest@project.com](OpenSourceRequest@project.com) distribution list;
 - add this library to the [open source libraries list](https://www.quora.com/What-is-an-open-source-library) indicating that it needs approval.

5. Once the library has been approved, it can be used in the project upon request from a project team member.

## Open Source Libraries List

You can find the list of open source libraries and their approval status [here][8]. 

## <a id="resources"></a> Resources

If you would like to learn more about license types and what you can and cannot do as regards licenses, please use the following resources:

- [A Short Guide to Open-Source and Similar Licenses](http://www.smashingmagazine.com/2010/03/24/a-short-guide-to-open-source-and-similar-licenses/);

- [Software Licenses & Summaries](https://tldrlegal.com/) - will explain licenses in plain English and show what you can and cannot do with them;

- [Jeff Atwood's analysis of open source licenses ](http://www.codinghorror.com/blog/2007/04/pick-a-license-any-license.html) (scroll down to the table).


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[2]: http://opensource.org/licenses/MIT
[3]: http://en.wikipedia.org/wiki/BSD_licenses
[4]: http://www.gnu.org/copyleft/lesser.html
[5]: https://www.gnu.org/copyleft/gpl.html
[6]: http://www.gnu.org/licenses/gpl-2.0.html
[7]: http://www.gnu.org/licenses/agpl-3.0.html
[8]: https://www.quora.com/What-is-an-open-source-library

> Written with [StackEdit](https://stackedit.io/).