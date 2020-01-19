<a href="https://www.itechart.by/"><img src="https://jobs.tut.by/employer-logo/1044984.png" title="iTechartLogo" alt="iTechartLogo"></a>
# .NET Mentoring Program

> Materials for each topic include videos, links to articles, documentation, titles of related books.

*Table of contents:*

- [.NET](#net)
   - [.NET Core / .NET Framework difference](#net-core--net-framework-difference)
   - [.NET Standard /.NET Framework compatibility](#net-standard-net-framework-compatibility)
- [C#](#c)
   - [Exceptions](#exceptions)
   - [Collections](#collections)
   - [Generics](#generics)
   - [Events and callbacks](#events-and-callbacks)
   - [Threads](#threads)
   - [Tasks](#tasks)
   - [Asynchronous programming](#asynchronous-programming)
   - [LINQ](#linq)
   - [Reflection](#reflection)
   - [GC](#gc)
   - [Serialization](#serialization)
   - [Assembly](#assembly)
- [Authentication/Authorization](#authenticationauthorization)
   - [Identity server](#identity-server) 
   - [Auth Types](#auth-types)
   - [SSO](#sso)
   - [Authentication vs Authorization](#authentication-vs-authorization)
- [Architecture](#architecture)
   - [SOLID](#solid)
   - [GOF patterns](#gof-patterns)
   - [Monolith](#monolith)
   - [SOA](#soa)
   - [CQRS](#cqrs)
   - [DDD](#ddd)
   - [TDD](#tdd)
   - [Clean architecture](#clean-architecture)
- [Encription/Decryption](#encriptiondecryption)
   - [Symmetric and asymmetric encryption](#symmetric-and-asymmetric-encryption)
   - [Digital signatures and certificates](#digital-signatures-and-certificates)
- [Cloud Providers](#cloud-providers)
   - [AWS/MS Azure/Google](#awsms-azuregoogle)
   - [Cloud Design Patterns](#cloud-design-patterns)
   - [Understanding of IaaS/PaaS/SaaS...aaS terms, etc.](#understanding-of-iaaspaassaasaas-terms-etc)

---


## .NET


### .NET Core / .NET Framework difference

- Videos: 
   - [.NET Core vs .NET Framework - What's the difference?](https://www.youtube.com/watch?v=79UWvR734wI) 
   - [Оптимизации внутри .NET Core](https://www.youtube.com/watch?v=n3-j_sTtGb0) 

-  Documentation: 
   - [Choose between .NET Core and .NET Framework for server apps](https://docs.microsoft.com/en-us/dotnet/standard/choosing-core-framework-server)
   - [About .NET Core](https://docs.microsoft.com/en-us/dotnet/core/about)
   - [Port from .NET Framework to .NET Core - .NET Core](https://docs.microsoft.com/en-us/dotnet/core/porting/)


### .NET Standard /.NET Framework compatibility

-  Documentation: 
   - [.NET Standard](https://docs.microsoft.com/en-us/dotnet/standard/net-standard)



---

## C#


- Books:
   - CLR via C#, by Jeffrey Richter
   - C# in Depth, by Jon Skeet
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)
   - C# 8.0 and .NET Core 3.0 – Modern Cross-Platform Development: Build applications with C#, .NET Core, Entity Framework Core, ASP.NET Core, and ML.NET using Visual Studio Code, 4th Edition by Mark J. Price

### Exceptions

-  Documentation: 
   - [Handling and throwing exceptions in .NET](https://docs.microsoft.com/en-us/dotnet/standard/exceptions/)
   


### Collections

- Videos: 
   - [Многопоточные структуры данных в .NET: как это работает?](https://www.youtube.com/watch?v=fQhz2iHmwV8) 

-  Documentation: 
   - [Collections and Data Structures](https://docs.microsoft.com/en-us/dotnet/standard/collections/)
   - [Generic Collections in .NET](https://docs.microsoft.com/en-us/dotnet/standard/generics/collections)
   - [BlockingCollection Overview](https://docs.microsoft.com/en-us/dotnet/standard/collections/thread-safe/blockingcollection-overview)
   - [Thread-Safe Collections](https://docs.microsoft.com/en-us/dotnet/standard/collections/thread-safe/)


### Generics

-  Documentation: 
   - [Generics - C# Programming Guide](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/generics/)


### Events and callbacks

-  Useful links: 
   - [Observer pattern](https://en.wikipedia.org/wiki/Observer_pattern) 
   - [Design Patterns - Observer Pattern - Tutorialspoint](https://www.tutorialspoint.com/design_pattern/observer_pattern.htm)
   - [Push VS Pull : Observer Pattern - THE DEDUCTION LEARNING](https://deductionlearning.com/design-patterns/push-vs-pull-observer-pattern/) 


-  Documentation: 
   - [Events and Callbacks](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/events-and-callbacks)
   - [Handling and Raising Events](https://docs.microsoft.com/en-us/dotnet/standard/events/)


- Books:
   -  Паттерны проектирования на платформе .NET, Сергей Тепляков. Observer pattern. Pull/Push model.


### Threads
*This section includes next subtopics:*
1. **Thread pool**
2. **Resource allocation**
3. **Threads switching**
4. **Threads synchronization**

- Books:
   -  CLR via C#, by Jeffrey Richter
   -  Exam Ref 70-483 Programming in C# by Rob Miles (second edition)



### Tasks
*This section includes next subtopics:*
1.  **Task Scheduler**
2.  **Task Continuation**
3.  **Task Cancellation**

-  Documentation: 
   - [Task Parallel Library (TPL)](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/task-parallel-library-tpl)

- Books:
   -  CLR via C#, by Jeffrey Richter
   -  Exam Ref 70-483 Programming in C# by Rob Miles (second edition)


### Asynchronous programming

- Videos: 
   - [Async programming in .NET: Best practices](https://www.youtube.com/watch?v=wM-h6P1BJRk) 
   - [Yield и async-await: как оно все устроено внутри и как этим воспользоваться](https://www.youtube.com/watch?v=TFsT8bgs024) 
   - [Многопоточные структуры данных в .NET: как это работает?](https://www.youtube.com/watch?v=fQhz2iHmwV8)
   - [Async/await](https://www.youtube.com/watch?v=lh8cT6qI-nA)
   - [Debugging asynchronous scenarios in .NET](https://www.youtube.com/watch?v=8Ans2u4Bsi8)
   - [Многопоточность в .NET: когда производительности не хватает](https://www.youtube.com/watch?v=-tNeYjRNJtY)
   - [Yield at me, 'cause I'm awaiting: асинхронные итераторы в C# 8](https://www.youtube.com/watch?v=ys2SrUel1aY&list=PLtWrKx3nUGBeA-AJe-UIik5g_7WImNn0S&index=16)
   - [Многопоточное и асинхронное программирование в .NET.](https://www.youtube.com/watch?v=mtTZu8CXaGE)

-  Documentation: 
   - [Asynchronous programming in C#](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
   - [The Task Asynchronous Programming Model (TAP) with async and await (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/task-asynchronous-programming-model)
   - [Walkthrough: Accessing the Web by Using async and await (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/walkthrough-accessing-the-web-by-using-async-and-await)
   - [How to extend the async walkthrough by using Task.WhenAll (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/how-to-extend-the-async-walkthrough-by-using-task-whenall)
   - [How to make multiple web requests in parallel by using async and await (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/how-to-make-multiple-web-requests-in-parallel-by-using-async-and-await)
   - [Fine-Tuning Your Async Application (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/fine-tuning-your-async-application)
   - [Cancel an Async Task or a List of Tasks (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/cancel-an-async-task-or-a-list-of-tasks)
   - [Cancel Async Tasks after a Period of Time (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/cancel-async-tasks-after-a-period-of-time)


- Books:
   -  CLR via C#, by Jeffrey Richter
   -  Exam Ref 70-483 Programming in C# by Rob Miles (second edition)



### LINQ
*This section includes next subtopics:*
1. [LINQ to SQL](#linq-to-sql)
2. [LINQ to Objects](#linq-to-objects)
3. [Parallel LINQ](#parallel-linq)

#### LINQ to SQL

-  Documentation: 
   - [LINQ to SQL](https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/sql/linq/)
   - [What You Can Do With LINQ to SQL](https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/sql/linq/what-you-can-do-with-linq-to-sql)
   - [Typical Steps for Using LINQ to SQL](https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/sql/linq/typical-steps-for-using-linq-to-sql)


- Books:
   - C# in Depth, by Jon Skeet
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)

#### LINQ to Objects

-  Documentation: 
   - [LINQ to Objects (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/linq-to-objects)
   - [How to add custom methods for LINQ queries (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/how-to-add-custom-methods-for-linq-queries)
   - [How to query an assembly's metadata with Reflection (LINQ) (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/how-to-query-an-assembly-s-metadata-with-reflection-linq)

- Books:
   - C# in Depth, by Jon Skeet
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)
   - C# 8.0 and .NET Core 3.0 – Modern Cross-Platform Development: Build applications with C#, .NET Core, Entity Framework Core, ASP.NET Core, and ML.NET using Visual Studio Code, 4th Edition by Mark J. Price

#### Parallel LINQ

-  Documentation: 
   - [Introduction to PLINQ](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/introduction-to-plinq)
   - [Parallel LINQ (PLINQ)](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/parallel-linq-plinq)


- Books:
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)

### Reflection
*This section includes next subtopics:*
1. [Attributes](#attributes)
2. [Assembly Load](#assembly-load)
3. [Dynamic generation](#dynamic-generation)

- Videos: 
   - [Деревья выражений в enterprise-разработке](https://www.youtube.com/watch?v=J2XzsCoJM4o)

-  Documentation: 
   - [Reflection (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/reflection)
   - [Retrieving Information Stored in Attributes](https://docs.microsoft.com/en-us/dotnet/standard/attributes/retrieving-information-stored-in-attributes)
   - [Dynamically Loading and Using Types](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/dynamically-loading-and-using-types)
   - [How to: Get type and member information by using reflection](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/get-type-member-information)
   - [Viewing Type Information](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/viewing-type-information)
   - [Reflection and Generic Types](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/reflection-and-generic-types)
   - [How to: Examine and Instantiate Generic Types with Reflection](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/how-to-examine-and-instantiate-generic-types-with-reflection)

- Books:
   - CLR via C#, by Jeffrey Richter
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)

#### Attributes

-  Documentation: 
   - [Attribute Class (System)](https://docs.microsoft.com/en-us/dotnet/api/system.attribute?view=netcore-3.0)
   - [Extending Metadata Using Attributes](https://docs.microsoft.com/en-us/dotnet/standard/attributes/)
   - [Applying Attributes](https://docs.microsoft.com/en-us/dotnet/standard/attributes/applying-attributes)
   - [Writing Custom Attributes](https://docs.microsoft.com/en-us/dotnet/standard/attributes/writing-custom-attributes)
   - [Retrieving Information Stored in Attributes](https://docs.microsoft.com/en-us/dotnet/standard/attributes/retrieving-information-stored-in-attributes)

- Books:
   - CLR via C#, by Jeffrey Richter
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)


#### Assembly Load

-  Documentation: 
   - [Assemblies in .NET](https://docs.microsoft.com/en-us/dotnet/standard/assembly/)
   - [Assembly contents](https://docs.microsoft.com/en-us/dotnet/standard/assembly/contents)
   - [Assembly manifest](https://docs.microsoft.com/en-us/dotnet/standard/assembly/manifest)
   - [Assemblies and side-by-side execution](https://docs.microsoft.com/en-us/dotnet/standard/assembly/side-by-side-execution)
   - [Create assemblies](https://docs.microsoft.com/en-us/dotnet/standard/assembly/create)
   - [Assembly names](https://docs.microsoft.com/en-us/dotnet/standard/assembly/names)
   - [Strong-named assemblies](https://docs.microsoft.com/en-us/dotnet/standard/assembly/strong-named)
   - [Create and use strong-named assemblies](https://docs.microsoft.com/en-us/dotnet/standard/assembly/create-use-strong-named)
   - [How to: Create a public-private key pair](https://docs.microsoft.com/en-us/dotnet/standard/assembly/create-public-private-key-pair)
   - [AppDomain Class (System)](https://docs.microsoft.com/en-us/dotnet/api/system.appdomain?view=netframework-4.8)
   - [How to: Load Assemblies into an Application Domain](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/how-to-load-assemblies-into-an-application-domain)
   - [AssemblyLoadContext Class (System.Runtime.Loader)](https://docs.microsoft.com/en-us/dotnet/api/system.runtime.loader.assemblyloadcontext?view=netcore-3.1)

- Books:
   - CLR via C#, by Jeffrey Richter


#### Dynamic generation

-  Documentation: 
   - [Compile and generate dynamic source code](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/dynamic-source-code-generation-and-compilation)
   - [Using the CodeDOM](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/using-the-codedom)
   - [How to: Create a Class Using CodeDOM](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/how-to-create-a-class-using-codedom)
   - [Dynamically Loading and Using Types](https://docs.microsoft.com/en-us/dotnet/framework/reflection-and-codedom/dynamically-loading-and-using-types)


- Books:
   - CLR via C#, by Jeffrey Richter
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)


### GC
*This section includes next subtopics:*
1. [Heap, Large Object Heap](#heap-large-object-heap)
2. [Generations](#generations)
3. [IDisposable / Finalize](#idisposable-finalize)

-  Documentation: 
   - [Garbage Collection](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/)
   - [Fundamentals of garbage collection](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/fundamentals)
   - [Garbage Collection and Performance](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/performance)
   - [Weak References](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/weak-references)

- Books:
   - CLR via C#, by Jeffrey Richter

#### Heap, Large Object Heap

-  Documentation: 
   - [LOH on Windows - .NET](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/large-object-heap)


#### Generations

-  Documentation: 
   - [Fundamentals of garbage collection](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/fundamentals)

#### IDisposable / Finalize

- Documentation: 
   - [Difference Between dispose( ) and finalize( ) in C# (with Comparison Chart) - Tech Differences](https://techdifferences.com/difference-between-dispose-and-finalize-in-c-sharp.html)
   - [IDisposable.Dispose Method (System)](https://docs.microsoft.com/en-us/dotnet/api/system.idisposable.dispose?view=netframework-4.8)
   - [Implementing a Dispose method](https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/implementing-dispose)
   - [Finalizers - C# Programming Guide](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/destructors)
   - [Object.Finalize Method (System)](https://docs.microsoft.com/en-us/dotnet/api/system.object.finalize?view=netframework-4.8)


### Serialization
*This section includes next subtopics:*
1. [XML](#xml)
2. [JSON](#json)
3. [Binary](#binary)

- Documentation: 
   - [Serialization (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/)

- Books:
   - CLR via C#, by Jeffrey Richter
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)

#### XML

- Documentation: 
   - [How to write object data to an XML file (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/how-to-write-object-data-to-an-xml-file)
   - [How to read object data from an XML file (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/how-to-read-object-data-from-an-xml-file)

- Books:
   - CLR via C#, by Jeffrey Richter
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)


#### JSON

- Documentation: 
   - [JsonSerializer Class (System.Text.Json)](https://docs.microsoft.com/en-us/dotnet/api/system.text.json.jsonserializer?view=netcore-3.1)
   - [Json.NET - Newtonsoft](https://www.newtonsoft.com/json)
   - [Serializing and Deserializing JSON](https://www.newtonsoft.com/json/help/html/SerializingJSON.htm)
   - [How to serialize and deserialize (marshal and unmarshal) JSON in .NET](https://docs.microsoft.com/en-us/dotnet/standard/serialization/system-text-json-how-to)


#### Binary

- Documentation: 
   - [Binary serialization](https://docs.microsoft.com/en-us/dotnet/standard/serialization/binary-serialization)
   - [SerializableAttribute Class (System)](https://docs.microsoft.com/en-us/dotnet/api/system.serializableattribute?view=netframework-4.8)
   - [Selective serialization](https://docs.microsoft.com/en-us/dotnet/standard/serialization/selective-serialization)
   - [Serialization guidelines](https://docs.microsoft.com/en-us/dotnet/standard/serialization/serialization-guidelines)

- Books:
   - CLR via C#, by Jeffrey Richter
   - Exam Ref 70-483 Programming in C# by Rob Miles (second edition)


### Assembly
*This section includes next subtopics:*
1. [GAC](#gac)
2. [Assembly management](#assembly-management)
3. [ILDasm/DotPeek disassembling tools](#ildasmdotpeek-disassembling-tools)

#### GAC

- Documentation: 
   - [Global Assembly Cache](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/gac)
   - [How to: Install an assembly into the global assembly cache](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/install-assembly-into-gac)
   - [Working with Assemblies and the Global Assembly Cache](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/working-with-assemblies-and-the-gac)
   - [How to: View the contents of the global assembly cache](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/how-to-view-the-contents-of-the-gac)
   - [How to: Remove an Assembly from the Global Assembly Cache](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/how-to-remove-an-assembly-from-the-gac)

- Books:
   - CLR via C#, by Jeffrey Richter

#### Assembly management

-  Documentation: 
   - [Assemblies in .NET](https://docs.microsoft.com/en-us/dotnet/standard/assembly/)
   - [Assembly contents](https://docs.microsoft.com/en-us/dotnet/standard/assembly/contents)
   - [Assembly manifest](https://docs.microsoft.com/en-us/dotnet/standard/assembly/manifest)
   - [Assemblies and side-by-side execution](https://docs.microsoft.com/en-us/dotnet/standard/assembly/side-by-side-execution)
   - [Create assemblies](https://docs.microsoft.com/en-us/dotnet/standard/assembly/create)
   - [Assembly names](https://docs.microsoft.com/en-us/dotnet/standard/assembly/names)
   - [Strong-named assemblies](https://docs.microsoft.com/en-us/dotnet/standard/assembly/strong-named)
   - [Create and use strong-named assemblies](https://docs.microsoft.com/en-us/dotnet/standard/assembly/create-use-strong-named)
   - [How to: Create a public-private key pair](https://docs.microsoft.com/en-us/dotnet/standard/assembly/create-public-private-key-pair)
   - [AppDomain Class (System)](https://docs.microsoft.com/en-us/dotnet/api/system.appdomain?view=netframework-4.8)
   - [How to: Load Assemblies into an Application Domain](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/how-to-load-assemblies-into-an-application-domain)

#### ILDasm/DotPeek disassembling tools

-  Useful links: 
   - [dotPeek — бесплатный инструмент для декомпиляции и исследования сборок .NET от JetBrains](https://www.jetbrains.com/ru-ru/decompiler/) 

-  Documentation: 
   - [Ildasm.exe (IL Disassembler)](https://docs.microsoft.com/en-us/dotnet/framework/tools/ildasm-exe-il-disassembler)

- Books:
   - CLR via C#, by Jeffrey Richter


---

## Authentication/Authorization

- Videos: 
   - [What is OAuth 2.0 and OpenID Connect?](https://www.youtube.com/watch?v=LyqeHAkxVyk)
   - [An Introduction To OpenID Connect](https://www.youtube.com/watch?v=6DxRTJN1Ffo)
   - [OAuth 2.0: An Overview](https://www.youtube.com/watch?v=CPbvxxslDTU)
   - [OAuth 2.0 and OpenID Connect](https://www.youtube.com/watch?v=996OiexHze0)



###  Identity server

- Videos: 
   - [Построение SSO на примере Identity Server 4.0 (.NET Core 2.0)](https://www.youtube.com/watch?v=6Y7Glw6NzLM)
   - [IdentityServer4: New & Improved for ASP.NET Core](https://www.youtube.com/watch?v=YXdJ2HLAOdE)

-  Documentation: 
   - [IdentityServer4](http://docs.identityserver.io/en/latest/) 

### Auth Types
*This section includes next subtopics:*
1. [OAuth](#oauth)
2. [Cookie-based](#cookie-based)
3. [Token-based](#token-based)

#### OAuth

- Videos: 
   - [Introduction to OAuth 2.0 and OpenID Connect ](https://www.youtube.com/watch?v=GyCL8AJUhww)

-  Documentation: 
   - [OAuth 2.0](https://oauth.net/2/) 
   - [OAuth.com - OAuth 2.0 Servers](https://www.oauth.com/) 
   - [OWIN OAuth 2.0 Authorization Server](https://docs.microsoft.com/en-us/aspnet/aspnet/overview/owin-and-katana/owin-oauth-20-authorization-server)

- Books:
   -  OAuth 2 in Action 1st Edition by Justin Richer

#### Cookie-based

- Videos: 
   - [Difference between cookies, session and tokens](https://www.youtube.com/watch?v=44c1t_cKylo)

-  Useful links: 
   - [Cookies vs. Tokens: The Definitive Guide - DZone Integration](https://dzone.com/articles/cookies-vs-tokens-the-definitive-guide) 


#### Token-based

- Videos: 
   - [Difference between cookies, session and tokens](https://www.youtube.com/watch?v=44c1t_cKylo)

-  Useful links: 
   - [Token Based Authentication Made Easy - Auth0](https://auth0.com/learn/token-based-authentication-made-easy/)


### SSO
*This section includes next subtopics:*
1. **SAML**
2. **OpenID Connect**

- Videos: 
   - [Построение SSO на примере Identity Server 4.0 (.NET Core 2.0)](https://www.youtube.com/watch?v=6Y7Glw6NzLM)
   - [SSO на базе OpenId Connect в корпоративной системе](https://www.youtube.com/watch?v=bF0JhYxeg7I)

-  Useful links: 
   - [Single sign-on](https://en.wikipedia.org/wiki/Single_sign-on)

-  Documentation: 
   - [Single sign-on to applications - Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/what-is-single-sign-on)
   - [Azure AD Connect: Seamless Single Sign-On](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso)
   - [Enterprise Single Sign-On](https://docs.microsoft.com/en-us/host-integration-server/esso/enterprise-single-sign-on1)


### Authentication vs Authorization

-  Useful links: 
   - [Authentication vs Authorization](https://medium.com/datadriveninvestor/authentication-vs-authorization-716fea914d55)
   - [How to implement Multi-Factor Authentication (MFA) - Microsoft Security](https://www.microsoft.com/security/blog/2020/01/15/how-to-implement-multi-factor-authentication/)

-  Documentation: 
   - [Authentication and Authorization in ASP.NET Web API](https://docs.microsoft.com/en-us/aspnet/web-api/overview/security/authentication-and-authorization-in-aspnet-web-api)


---

## Architecture

###  SOLID
*This section includes next subtopics:*
1. [Single Responsibility](#single-responsibility)
2. [Open-closed](#open-closed)
3. [Liskov Substution](#liskov-substution)
4. [Interface Segregation](#interface-segregation)
5. [Dependency Inversion](#dependency-inversion)

- Videos: 
   - [SOLID principles](https://www.youtube.com/watch?v=zHiWqnTWsn4) 
   - [The S.O.L.I.D. Principles of OO and Agile Design](https://www.youtube.com/watch?v=t86v3N4OshQ&list=RDzHiWqnTWsn4&index=2) 

-  Documentation: 
   - [The Principles of OOD](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)

- Books:
   -  Clean Architecture: A Craftsman's Guide to Software Structure and Design (Robert C. Martin Series)


#### Single Responsibility

-  Documentation: 
   - [SRP: The Single Responsibility Principle](https://drive.google.com/file/d/0ByOwmqah_nuGNHEtcU5OekdDMkk/view)

#### Open-closed

-  Documentation: 
   - [The Open-Closed Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1/view)

#### Liskov Substution

-  Documentation: 
   - [The Liskov Substitution Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh/view)

#### Interface Segregation

-  Documentation: 
   - [The Interface Segregation Principle](https://drive.google.com/file/d/0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi/view)

#### Dependency Inversion

-  Documentation: 
   - [SOLID Design Principles Explained: Dependency Inversion Principle with Code Examples](https://stackify.com/dependency-inversion-principle/)


### GOF patterns
*This section includes next subtopics:*
1. [Strategy](#strategy)
2. [Template Method](#template-method)
3. [Mediator](#mediator)
4. [Iterator](#iterator)
5. [Observer](#observer)
6. [Visitor](#visitor)
7. [Singleton](#singleton)
8. [Abstract Factory](#abstract-factory)
9. [Factory Method](#factory-method)
10. [Builder](#builder)
11. [Adapter](#adapter)
12. [Facade](#facade)
13. [Decorator](#decorator)
14. [Composite](#composite)
15. [Proxy](#proxy)
16. [Command](#command)
17. [Chain of Responsibility](#chain-of-responsibility)


- Videos: 
   - [Adapter Design Pattern](https://www.youtube.com/watch?v=qG286LQM6BU&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd)

-  Useful links: 
   - [Gang of Four Design Patterns](http://www.blackwasp.co.uk/gofpatterns.aspx)

- Books:
   -  Паттерны проектирования на платформе .NET, Сергей Тепляков, 2018


#### Strategy

- Videos: 
   - [Strategy Design Pattern](https://www.youtube.com/watch?v=-NCgRD9-C6o&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=17)

-  Useful links: 
   - [Strategy Design Pattern](http://www.blackwasp.co.uk/Strategy.aspx)

#### Template Method

- Videos: 
   - [Template Method Design Pattern](https://www.youtube.com/watch?v=aR1B8MlwbRI&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=5)

-  Useful links: 
   - [Template Method Design Pattern](http://blackwasp.co.uk/TemplateMethod.aspx)

#### Mediator

- Videos: 
   - [Mediator Design Pattern](https://www.youtube.com/watch?v=8DxIpdKd41A&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=3)

-  Useful links: 
   - [Mediator Design Pattern](http://www.blackwasp.co.uk/Mediator.aspx)

#### Iterator

-  Useful links: 
   - [Iterator Design Pattern](http://www.blackwasp.co.uk/Iterator.aspx)

#### Observer

- Videos: 
   - [Observer Design Pattern](https://www.youtube.com/watch?v=wiQdrH2YpT4&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=13)

-  Useful links: 
   - [Observer Design Pattern](http://www.blackwasp.co.uk/Observer.aspx)

#### Visitor

- Videos: 
   - [Visitor Design Pattern](https://www.youtube.com/watch?v=pL4mOUDi54o&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=15)

-  Useful links: 
   - [Visitor Design Pattern](http://www.blackwasp.co.uk/Visitor.aspx)

#### Singleton

-  Useful links: 
   - [Singleton Design Pattern](http://www.blackwasp.co.uk/Singleton.aspx)

#### Abstract Factory

- Videos: 
   - [Abstract Factory Design Pattern](https://www.youtube.com/watch?v=xbjAsdAK4xQ&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=9)

-  Useful links: 
   - [Abstract Factory Design Pattern](http://www.blackwasp.co.uk/AbstractFactory.aspxv)

#### Factory Method

- Videos: 
   - [Factory Design Pattern](https://www.youtube.com/watch?v=ub0DXaeV6hA&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=14)

-  Useful links: 
   - [Factory Design Pattern](http://www.blackwasp.co.uk/FactoryMethod.aspx)

#### Builder

-  Useful links: 
   - [Builder Design Pattern](http://www.blackwasp.co.uk/Builder.aspx)


#### Adapter

- Videos: 
   - [Adapter Design Pattern](https://www.youtube.com/watch?v=qG286LQM6BU&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=1)

-  Useful links: 
   - [Adapter Design Pattern](http://www.blackwasp.co.uk/Adapter.aspx)

#### Facade

-  Useful links: 
   - [Facade Design Pattern](http://www.blackwasp.co.uk/Facade.aspx)

#### Decorator

- Videos: 
   - [Decorator Design Pattern](https://www.youtube.com/watch?v=j40kRwSm4VE&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=4)

-  Useful links: 
   - [Decorator Design Pattern](http://www.blackwasp.co.uk/Decorator.aspx)

#### Composite

-  Useful links: 
   - [Composite Design Pattern](http://www.blackwasp.co.uk/Composite.aspx)

#### Proxy

- Videos: 
   - [Proxy Design Pattern Tutorial](https://www.youtube.com/watch?v=cHg5bWW4nUI&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=6)

-  Useful links: 
   - [Proxy Design Pattern](http://www.blackwasp.co.uk/Proxy.aspx)


#### Command

- Videos: 
   - [Command Design Pattern](https://www.youtube.com/watch?v=7Pj5kAhVBlg&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=11)

-  Useful links: 
   - [Command Design Pattern](http://www.blackwasp.co.uk/Command.aspx)

#### Chain of Responsibility

- Videos: 
   - [Chain of Responsibility Design Pattern](https://www.youtube.com/watch?v=jDX6x8qmjbA&list=PLhkg-R66TRTV1-mDPLQ1HL7Wk9dGRBgSd&index=8)

-  Useful links: 
   - [Chain of Responsibility Design Pattern](http://www.blackwasp.co.uk/ChainOfResponsibility.aspx)


### Monolith

-  Documentation: 
   - [Common web application architectures](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures)

- Books:
   -  Clean Architecture: A Craftsman's Guide to Software Structure and Design (Robert C. Martin Series


### SOA

- Videos: 
   - [Building microservices with .NET Core and Docker](https://www.youtube.com/watch?v=-AfZxdXa7yc) 
   - [I have a microservices architecture and I didn't know](https://www.youtube.com/watch?v=52SN8VB_3vs) 

-  Useful links: 
   - [Service-oriented architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture) 
   - [Microservices vs SOA - Know The Difference](https://www.leanix.net/en/blog/microservices-vs-soa) 
   - [What are microservices?](https://microservices.io/) 

-  Documentation: 
   - [Microservices vs. SOA — Is There Any Difference at All?](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/)

- Books:
   -  Microservices Patterns: With examples in Java, by Chris Richardson
   -  Microsoft .NET - Architecting Applications for the Enterprise (Developer Reference) 2nd Edition, by Dino Esposito
   -  Patterns of Enterprise Application Architecture, by Martin Fowler

###  CQRS

- Videos: 
   - [Event Sourcing и CQRS на конкретном примере](https://www.youtube.com/watch?v=AKGT7wkVd34) 
   - [Event Sourcing in Production - Real-Time CQRS/DDD .NET Apps with EventStore](https://www.youtube.com/watch?v=t2AI9hODJ2E) 

-  Useful links: 
   - [Microservices Pattern: Command Query Responsibility Segregation (CQRS)](https://microservices.io/patterns/data/cqrs.html) 

-  Documentation: 
   - [Command and Query Responsibility Segregation (CQRS) pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
   - [Applying simplified CQRS and DDD patterns in a microservice](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/apply-simplified-microservice-cqrs-ddd-patterns)
   - [.NET Microservices. Architecture for Containerized .NET Applications](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/)

- Books:
   -  Microsoft .NET - Architecting Applications for the Enterprise (Developer Reference) 2nd Edition, by Dino Esposito
   -  Patterns of Enterprise Application Architecture, by Martin Fowler


### DDD

- Videos: 
   - [DDD Isn't Done: A Skeptical, Optimistic , Pragmatic Look](https://www.youtube.com/watch?v=R2IAgnpkBck) 
   - [Domain-driven design: рецепт для прагматика](https://www.youtube.com/watch?v=CR9mLGN9jh0) 
   - [Просто о сложном - Domain Driven Design](https://www.youtube.com/watch?v=7HXIrEsmlzM)
   - [Hands-on Experience: What It Means to Design a Domain Model](https://www.youtube.com/watch?v=3oO7gd16Xp0) 
   - [DDD: Where’s the Value and What’s in It for Me?](https://www.youtube.com/watch?v=6hkXkz4aQzQ) 
   - [What is DDD](https://www.youtube.com/watch?v=pMuiVlnGqjk)

-  Documentation: 
   - [Designing a DDD-oriented microservice](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/ddd-oriented-microservice)
   - [Designing a microservice domain model](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/microservice-domain-model)
   - [Implementing a microservice domain model with .NET Core](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/net-core-microservice-domain-model)

- Books:
   -  Domain-Driven Design: Tackling Complexity in the Heart of Software, by Eric Evans
   -  Implementing Domain-Driven Design, by Vaughn Vernon 


### TDD

- Videos: 
   - [TDD вверх ногами](https://www.youtube.com/watch?v=3QT7jaoOa9w/) 

-  Useful links: 
   - [Test-driven development](https://en.wikipedia.org/wiki/Test-driven_development)

-  Documentation: 
   - [Walkthrough: Test-driven development using Test Explorer](https://docs.microsoft.com/en-us/visualstudio/test/quick-start-test-driven-development-with-test-explorer?view=vs-2019)
   - [Use Microsoft.VisualStudio.TestTools.UnitTesting in unit tests - Visual Studio](https://docs.microsoft.com/en-us/visualstudio/test/using-microsoft-visualstudio-testtools-unittesting-members-in-unit-tests?view=vs-2019)
   - [MSTest assert classes and methods - Visual Studio](https://docs.microsoft.com/en-us/visualstudio/test/using-the-assert-classes?view=vs-2019)
   - [Unit tests for generic methods](https://docs.microsoft.com/en-us/visualstudio/test/unit-tests-for-generic-methods?view=vs-2019)


- Books:
   -  Clean Architecture: A Craftsman's Guide to Software Structure and Design (Robert C. Martin Series)


### Clean architecture
*This section includes next subtopics:*
1. **onion**
2. **hexagonal**
**etc.**

- Videos: 
   - [Clean Architecture with ASP.NET Core 2.1](https://www.youtube.com/watch?v=_lwCVE_XgqI) 
   - [Эволюция Enterprise-архитектур. От MVC до Clean Architecture](https://www.youtube.com/watch?v=WXelYPjwmk0) 
   - [Clean Architecture with ASP.NET Core 3.0](https://www.youtube.com/watch?v=5OtUm1BLmG0) 

-  Useful links: 
   - [Hexagonal architecture (software)](https://en.wikipedia.org/wiki/Hexagonal_architecture_(software))
   - [Onion Architecture In ASP.NET Core MVC - TechNet Articles](https://social.technet.microsoft.com/wiki/contents/articles/36655.onion-architecture-in-asp-net-core-mvc.aspx)

-  Documentation: 
   - [Common web application architectures](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures#clean-architecture)

- Books:
   -  Clean Architecture: A Craftsman's Guide to Software Structure and Design (Robert C. Martin Series)


---

## Encription/Decryption

- Videos: 
   - [Подводные камни System.Security.Cryptography](https://www.youtube.com/watch?v=X1V6_OyQKLw) 
   - [Pitfalls of high-level cryptography](https://www.youtube.com/watch?v=ZqGyV7Jshww) 
   - [Free SSL with Let's Encrypt](https://www.youtube.com/watch?v=bcdyLIwASM4)

- Books:
   -  Exam Ref 70-483 Programming in C# by Rob Miles (second edition)

###  Symmetric and asymmetric encryption

- Videos: 
   - [Asymmetric encryption - Simply explained](https://www.youtube.com/watch?v=AQDCe585Lnc) 
   - [The RSA Encryption Algorithm (1 of 2: Computing an Example)](https://www.youtube.com/watch?v=4zahvcJ9glg) 
   - [The RSA Encryption Algorithm (2 of 2: Generating the Keys)](https://www.youtube.com/watch?v=oOcTVTpUsPQ)

-  Useful links: 
   - [Advanced Encryption Standard](https://ru.wikipedia.org/wiki/Advanced_Encryption_Standard) 
   - [C# Symmetric Encryption - Visual C# Kicks](http://www.vcskicks.com/symmetric-encryption.php) 
   - [C# Symmetric Encryption - Page 2 - Visual C# Kicks](http://www.vcskicks.com/symmetric-encryption2.php) 
   - [Public-key cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography) 
   - [DES (Data Encryption Standard)](https://ru.wikipedia.org/wiki/DES)
   - [Triple DES](https://ru.wikipedia.org/wiki/Triple_DES) 
   - [SHA-1](https://ru.wikipedia.org/wiki/SHA-1)
   - [SHA-2](https://ru.wikipedia.org/wiki/SHA-2)
   - [SHA-3](https://ru.wikipedia.org/wiki/SHA-3)
   - [RSA](https://ru.wikipedia.org/wiki/RSA)
   - [The Legion of the Bouncy Castle C# Cryptography APIs](http://www.bouncycastle.org/csharp/)

-  Documentation: 
   - [System.Security.Cryptography Namespace](https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography?view=netframework-4.8)
   - [AsymmetricAlgorithm Class (System.Security.Cryptography)](https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography.asymmetricalgorithm?view=netframework-4.8)
   - [RSA Class (System.Security.Cryptography)](https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography.rsa?view=netframework-4.8)


### Digital signatures and certificates

- Videos: 
   - [What are certificates?](https://www.youtube.com/watch?v=LRMBZhdFjDI) 
   - [Why digital certificate?](https://www.youtube.com/watch?v=UbMlPIgzTxc)
   - [Digital Signatures and Digital Certificates](https://www.youtube.com/watch?v=stsWa9A3sOM) 
   - [SSL Certificate C#](https://www.youtube.com/playlist?list=PLx9dWjE8mJNSamLl-7Xdprwpy2b5cieTG) 

-  Useful links: 
   - [Digital signature](https://en.wikipedia.org/wiki/Digital_signature) 
   - [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) 


---

## Cloud Providers

###  AWS/MS Azure/Google


- Videos: 
   - [Test](http://www.dropwizard.io/1.0.2/docs/) 
   - [Test](http://www.dropwizard.io/1.0.2/docs/) 
   - [Test](http://www.dropwizard.io/1.0.2/docs/) 

-  Useful links: 
   - [Test](http://www.dropwizard.io/1.0.2/docs/) 
   - [Test](http://www.dropwizard.io/1.0.2/docs/) 

-  Documentation: 
   - [Test](https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography?view=netframework-4.8)

- Books:
   -  Book1
   -  Book2

### Cloud Design Patterns

*This section includes next subtopics:*
1. [Understanding of Gateway pattern (Ocelot, Azure Gateway, etc)](#understanding-of-gateway-pattern-ocelot-azure-gateway-etc)
2. [Understanding external/internal communication ways (REST/Message Bus/etc)](#understanding-externalinternal-communication-ways-restmessage-busetc)
3. [Retry pattern (Polly, etc)](#retry-pattern-polly-etc)
4. [Circut Breaker pattern](#circut-breaker-pattern)
5. [Event sourcing pattern](#event-sourcing-pattern)
6. [Publisher/Subscriber pattern](#publishersubscriber-pattern)
7. [Aggregation pattern](#aggregation-pattern)
8. [Gateway routing pattern](#gateway-routing-pattern)
9. [CQRS: Command-Query Responsibility Segregation](#cqrs-command-query-responsibility-segregation)
10. [Understanding of availability, resiliency, messaging, management and monitoring, etc. terms](#understanding-of-availability-resiliency-messaging-management-and-monitoring-etc-terms)

-  Books: 
   - [.NET Microservices: Architecture for Containerized .NET Applications](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/)
   - Microsoft .NET - Architecting Applications for the Enterprise (Developer Reference) 2nd Edition by Dino Esposito
   - Patterns of Enterprise Application Architecture by Martin Fowler



#### Understanding of Gateway pattern (Ocelot, Azure Gateway, etc

- Videos: 
   - [API gateway made easy with Ocelot and containers](https://www.youtube.com/watch?v=U7I2Yli9NZw&list=PLtWrKx3nUGBeA-AJe-UIik5g_7WImNn0S&index=26) 

-  Useful links: 
   - [Github: ThreeMammals/Ocelot](https://github.com/ThreeMammals/Ocelot) 

-  Documentation: 
   - [Gateway Aggregation pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-aggregation) 
   - [Gateway Offloading pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-offloading)
   - [Gateway Routing pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-routing)


#### Understanding external/internal communication ways (REST/Message Bus/etc)

- Videos: 
   - [Messaging and Microservices](https://www.youtube.com/watch?v=rXi5CLjIQ9k) 

-  Documentation: 
   - [.NET Microservices. Architecture for Containerized .NET Applications](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/)


#### Retry pattern (Polly, etc)

-  Useful links: 
   - [Github: App-vNext/Polly](https://github.com/App-vNext/Polly) 

-  Documentation: 
   - [Implement HTTP call retries with exponential backoff with Polly](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/implement-resilient-applications/implement-http-call-retries-exponential-backoff-polly) 
   - [Retry pattern - Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/retry)


#### Circut Breaker pattern

-  Documentation: 
   - [Circuit Breaker pattern - Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker) 

#### Event sourcing pattern

- Videos: 
   - [Design Patterns: Why Event Sourcing?](https://www.youtube.com/watch?v=rUDN40rdly8)

-  Documentation: 
   - [Event Sourcing pattern - Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)


#### Publisher/Subscriber pattern

-  Documentation: 
   - [Publisher-Subscriber pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/publisher-subscriber)



#### Aggregation pattern

-  Documentation: 
   - [Implementing a microservice domain model with .NET Core](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/net-core-microservice-domain-model)


#### Gateway routing pattern

-  Documentation: 
   - [Gateway Routing pattern - Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-routing)


#### CQRS: Command-Query Responsibility Segregation

- Videos: 
   - [ Event Sourcing и CQRS на конкретном примере](https://www.youtube.com/watch?v=AKGT7wkVd34)


-  Documentation: 
   - [Command and Query Responsibility Segregation (CQRS) pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
   - [Apply simplified CQRS and DDD patterns in a microservice](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/apply-simplified-microservice-cqrs-ddd-patterns)

#### Understanding of availability, resiliency, messaging, management and monitoring, etc. terms

-  Documentation: 
   - [Overview of the resiliency pillar](https://docs.microsoft.com/en-us/azure/architecture/framework/resiliency/overview)
   - [Overview of the scalability pillar](https://docs.microsoft.com/en-us/azure/architecture/framework/scalability/overview)
   
---

### Understanding of IaaS/PaaS/SaaS...aaS terms, etc.


-  Useful links: 
   - [SaaS vs PaaS vs IaaS: What’s The Difference and How To Choose](https://www.bmc.com/blogs/saas-vs-paas-vs-iaas-whats-the-difference-and-how-to-choose/) 


---

