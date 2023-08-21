# This will be a blog, until then..

## Programming languages

| Language       | Purpose        | Popularity     | Website                        |
|----------------|----------------|----------------|--------------------------------|
| Python         | General        | Very High      | [python.org](https://www.python.org/)             |
| JavaScript     | Web Dev        | Very High      | [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| Java           | General        | High           | [java.com](https://www.java.com/)                 |
| C++            | General        | High           | [isocpp.org](https://isocpp.org/)                 |
| C#             | General        | Moderate       | [docs.microsoft.com/dotnet/csharp](https://docs.microsoft.com/en-us/dotnet/csharp/) |
| Ruby           | Web Dev        | Moderate       | [ruby-lang.org](https://www.ruby-lang.org/en/)   |
| PHP            | Web Dev        | Moderate       | [php.net](https://www.php.net/)                 |
| Swift          | iOS Dev        | Moderate       | [swift.org](https://www.swift.org/)               |
| Kotlin         | Android Dev    | Moderate       | [kotlinlang.org](https://kotlinlang.org/)       |
| Go             | Systems        | Moderate       | [golang.org](https://golang.org/)               |

## Vulnerabilities

| Vulnerability                        | Description                                                                                            | Year |
|--------------------------------------|--------------------------------------------------------------------------------------------------------|------|
| SQL Injection                        | Allows attackers to execute arbitrary SQL queries on your database.                                | N/A  |
| Cross-Site Scripting (XSS)            | Permits attackers to inject malicious scripts into web pages viewed by users.                       | N/A  |
| Remote Code Execution (RCE)           | Allows attackers to execute code on the server remotely, often leading to full control.             | N/A  |
| File Inclusion Vulnerabilities       | Lets attackers include files from the server, potentially leading to code execution.                | N/A  |
| Command Injection                    | Allows execution of arbitrary system commands, potentially leading to server compromise.           | N/A  |
| Remote File Inclusion (RFI)           | Similar to file inclusion but specifically involves remote files, often leading to code execution.   | N/A  |
| Denial of Service (DoS)               | Attackers overwhelm a system, causing it to crash or become unavailable to users.                   | N/A  |
| Cross-Site Request Forgery (CSRF)     | Trick users into performing actions they didn't intend, often resulting in unauthorized actions.    | N/A  |
| Insecure Serialization               | Attackers manipulate serialized data to execute malicious code or gain unauthorized access.        | N/A  |
| Server-Side Request Forgery (SSRF)    | Allows attackers to make requests to internal resources, potentially leading to data exposure.     | N/A  |

## Architecture styles 
| Architecture Style          | Description                                                                                     | Common Use Cases                                        |
|-----------------------------|-------------------------------------------------------------------------------------------------|---------------------------------------------------------|
| Monolithic Architecture     | Single, self-contained application with all components tightly coupled.                       | Small to medium-sized applications.                    |
| Microservices Architecture  | Divides application into small, independent services that communicate via APIs.                | Scalable web applications with modular development.    |
| Client-Server Architecture  | Separates application into client (user interface) and server (logic and data).               | Web applications, email systems, remote access.       |
| Service-Oriented Architecture (SOA) | Components as services that communicate via well-defined protocols.                | Enterprise systems integrating diverse services.     |
| Event-Driven Architecture   | System responds to events, with event producers and consumers.                                 | Real-time applications, IoT systems.                  |
| Layered Architecture       | Divides components into logical layers (e.g., presentation, business logic, data access).      | Traditional web applications, enterprise software.   |
| Pipe and Filter Architecture | Data flows through a series of filters, each processing a part of the data.                   | Data processing, multimedia applications.            |
| Repository Architecture     | Centralized data store used by components, providing a consistent interface to data.           | Enterprise applications, data-driven systems.        |
| Peer-to-Peer Architecture   | Nodes communicate directly, enabling distributed systems without central coordination.         | File sharing, decentralized networks.               |
| Event-Sourcing Architecture | Captures all changes to an application's state as a sequence of events.                         | Financial systems, audit trails, complex workflows. |
| Domain-Driven Design (DDD)  | Focuses on modeling the domain and defining core concepts and their relationships.              | Complex business domains, software design clarity. |
| Big Data Architecture      | Handles processing, storage, and analysis of large datasets.                                   | Analytics platforms, large-scale data processing.  |
| Cloud-Native Architecture  | Optimized for cloud environments, often using containers and microservices.                    | Applications hosted on cloud platforms.            |
| Serverless Architecture    | Infrastructure managed by cloud provider, only runs code in response to events.                | Event-driven applications, microservices.         |
