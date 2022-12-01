# Computer Science Terms

## Word: Test Driven Development
### Description:
TDD is the software development approach in which we write the failing test of the action we want to code. Then we write the code of the action that passes the previously written test. Then we again write the failing test, and then code to pass that test. This iteration process continues for whole application development.  
In simple form: write test -> write code to pass the test -> write test -> write code to pass the test ......
#### search keywords: TDD, test, testing, test driven development
#### relevant words: Unit Testing, Integration Testing, Mock 
#### category: software development
#### scope: beginner


## Word: Unit Testing
### Decription:
Unit testing is TDD approach in which single methods/units of code are tested to see if they work, and are providing desired results.  
For example, Let's say your calculator application contains methods such as addition, and multiplication. Here, addition, is independent methods, while multiplication depends upon additoin. You may unit test addition by calling method on two random numbers to check if it is giving correct results.  
Once addition passes your tests, you can then use addition method to write multiplication logic without worrying about whether addition method will give wrong results.  
This way, if some error occurs, you can be sure that the error is not in addition method.
#### search keywords, unit test, tests, test, unit testing
#### relevant words: Test Driven Development,   
#### category: software development
#### scope: beginner


## Word: Job Scheduling
### Description:
Job Scheduling is the way of executing actions at specific time, either once or repitively. For example, you can schedule a random number generator to generate random numbers after every 2 hours.
#### search keywords: schedule, schedular, job scheduling
#### relevant words: cron, schedular  
#### category: software development, operating system
#### scope: beginner

## Word: Payment Gateway
### Description:
Payment gateway is a service used by organizations to sell their products and get the payment online from customers.  
Most companies use already built payment gateways instead of building their own for payment related actions.  
A payment gateway can be added into the application/project by following the guidelines provided by the gateway providing companies.  
Some common examples of payment gateways are PayPal, Paddle, fastSpring etc.
#### search keywords: payment, payment gateway, money
#### relevant words:  
#### category: software development
#### scope: beginner

## Word: ISP
### Description:
ISP(internet service provider) refers to a local company that provides internet access to users who are using its service.  
Typical examples of ISP are Cellular Internet Providers, Wifi Internet Providers etc.  
#### search keywords: isp, internet service provider, internet provider
#### relevant words:  
#### category: computer networks, operating system, software development
#### scope: beginner

## Word: Internet Standard
### Description:
Internet standard refers to approved guidelines that provide information about the correct use of a specific technology. For example, Internet Standard document [RFC 5321](https://datatracker.ietf.org/doc/html/rfc5321) provides guidelines about what SMTP is, and how to use it correctly.  
Internet Standards are approved by Internet Engineering Task Force(IEFT), a standard organization responsible for technical standards for internet.  
#### search keywords: internet standard, IEFT
#### relevant words:
#### category: computer networks
#### scope: advanced

## Word: Inversion of Control
### Description:
IoC is the programming principle in which the flow of code is controlled by framework rather than by yourself. In simple terms, instead of you calling the functions in your code to use them, the framework does this for you. You just have to initialize the class object with dependency injection into you code where you want to use the function. 
#### search keywords: inversion of control, ioc
#### relevant words: dependency injection
#### category: software development
#### scope: advanced

## Word: Secure Shell Protocol
### Description:
SSH protocol is the is a method of secure remote login from one computer to another computer. For example, you want to access your cloud server system on your personal computer. You will use secure shell protocol(ssh) to access the remote server securely.
#### search keywords: secure shell protocol, ssh, protocol, ssh-key
#### relevant words: ssh-key, remote
#### category: computer networks, software development
#### scope: advanced

## Word: ssh-key
### Description:
ssh-key is the secure, cryptographically generated key that is used in ssh protocol to have secure remote login from one computer to another. You generate ssh-key on the server you want to have remote access to(e.g. your cloud server), and you insert the key into the system you want to have remote access from(e.g your personal computer).
#### search keywords: ssh-key, ssh key, ssh
#### relevant words: secure shall protocol
#### category: computer networks, software development
#### scope: advanced

## Word: Version Control
### Description:
Version control is a system which allows us to manage changes in our code, and keep track of the the changes.  
A simple example of version control system is GitHub. It allows changes in code as well as keep record of all the changes occured. 
#### search keywords: version control, git
#### relevant words: git
#### category: software development
#### scope: beginner

## Word: Git
### Description:
Git is a version control and collaboration software used to track changes in any set of files.  
Git is different from Github in the sense that Github is one of many GUI implementations of Git. GitLab is another implementation that uses Git. 
#### search keywords: git, version control
#### relevant words: version control
#### category: software development
#### scope: beginner

## Word: Servlet
### Description:
Servelet is a small java program that runs inside a web server. A servlet ususally receives and responds to requests from web client(browser).  
For example, you build function that will add two numbers. You write a piece of code that will take numbers which are inputted into browser webpage, and shall return the result to the browser. That piece of code is called servlet.  
#### search keywords: servlet
#### relevant words: web client, rest, api
#### category: software development
#### scope: beginner

## Word: JIT
### Description:
JIT(just-in-time) compilation is a way of compiling a code snippet during code execution(runtime) rather than before code execution. In jit compilation, the code is compiled at runtime, but only that code snippet is compiled which is actually needed at that time.  
For example, you write two functions: addition and substraction. You execute the code, and it starts running. However, neither addition nor subsctarction codes snippets have been compiled yet. Now, you call addition functions in your code. At the moment, the addition function code snippet is compiled and is then executed.In that sense, JIT compilation is basically a dynamic compilation.
#### search keywords: jit, just in time
#### relevant words: compilation, aot, ahead-of-time,
#### category: software development
#### scope: advanced

## Word: AOT
### Description:
AOT(ahead-of-time) compilation is a way of compiling code in which all the code is compiled to machine interpretable code(in most cases) before code execution. A simple example is compilation of C language code. In a sense, AOT concept is opposite to JIT concept.
#### search keywords: aot, ahead of time
#### relevant words: compilation, jit, just-in-time
#### category: software development
#### scope: advanced

## Word: client
### Description:
In computer science domain, client is any hardware or software component that accesses some service/function made available by some other computer hardware/software (called server) as part of client-server model of computer networks.  
For example, when we write some search item on a search engine(e.g. google), our web browser acts as client which requests to access the service provided by google server.
#### search keywords: client
#### relevant words: server, client-server model
#### category: software development, computer networks
#### scope: beginner

## Word: server
### Description:
In computer seience domain, server is any hardware of software component that provides functionality/service for other programs called "clients".
For example, google search engine is a server that provides search functionality via the web browsers acting as clients.  
#### search keywords: server
#### relevant words: cleint, client-server model
#### category: software development, computer networks
#### scope: beginner

## Word: client-server model
### Description:
In computer science domain, client-server model is a computer networking model based on clients and servers.
#### search keywords: server
#### relevant words: client, server
#### category: software development, computer networks
#### scope: beginner

## Word: SQL Injection
SQL injection is a web security vulnerability that allows attacker to directly interact with our backend database without admin access, usually from front-end. For example, Let's there are two subscription plans: A and B in our database. One user has plan A, and he wants to delete it. Now, if we are passing plan id as parameter to backend, the user can simply change the plan Id in browser and some other plan will be deleted which did not belong to user.  
To avoid such issue, if it is necessary to pass table ids to backend, make sure to add proper checks on backend to validate the data. 
#### search keywords: sql injection, sql attacks, sql attack
#### relevant words: database
#### category, software development
#### scope: begineer

## Word: routing
### Description:
Routing is the process of selecting path for traffic from a network, or different networks.
For example, Let's say you want to visit facebook in china. Now,default china internet routing paths block facebook. So, you will need to use VPN which will send your facebook page request(traffic) via different path, thus routing your traffic to allows facebook page.
#### search keywords: routing
#### relevant words: routing
#### category: software development, computer networks
#### scope: beginner

## Word: Regional Internet Registery(RIR)
### Description:
RIR is an organization that manages the allocation and registeration of internet number resources within a specific region of the world. These internet number resources include IP addresses and autonomous systems(AS) numbers.
There are five RIRs for different regions of the world:
- RIPE NCC(Réseaux IP Européens Network Coordination Centre) serves Europe, Central Asia, Russia, and West Asia.
- LACNIC(Latin America and Caribbean Network Information Centre) serves most of the Caribbean and all of Latin America
- AFRINIC(African Network Information Center) serves Africa.
- ARIN(American Registry for Internet Numbers) serves Antarctica, Canada, parts of the Caribbean, and the United States.
- APNIC(Asia-Pacific Network Information Centre) serves East Asia, Oceania, South Asia, and Southeast Asia.
#### search keywords: RIR, internet registery
#### relevant words: registery
#### category: computer networks, cybersecurity
#### scope: medium,expert

## Word: Type introspection
### Description:
Type introspection is the ability of a programm/(programming language) to examine the type or properties of an object at runtime. For example, you can find out the type of an object, which class does it belongs to etc in some programming languages because of type intropection.
Some languages that support type introspection are java, python ruby etc.
#### search keywords: type introspection, type, intrspection, introspect
#### relevant words: reflective prgramming, reflection, type
#### category: software development
#### scope: medium,expert


## Word: Reflective Programming
### Description:
Reflective programming is the ability of a process to examine, introspect, and modify its own structure and behaviour. For a programming language, it is the ability of descovering the types and objects in an application, and being able to perform coded actions using those types.
Java supports reflective programming.
An example of reflective programming is the use of generics in java.
#### search keywords: reflection, reflective, reflective programming
#### relevant words: type introspection
#### category: software development
#### scope: medium,expert

## Word: Forward Proxy
### Description:
Forward proxy sits between client and internet, intercepts the requests sent by client and processes them before forwarding those requests to internet service. A simple example of forward proxy is vpn service, which changes the ip address of the request. So, in essence, a forward proxy hides the client from the internet.
A simple flow of a web request with forward proxy will be as follows:
client -> forward proxy -> internet
#### search keywords: proxy, forward proxy
#### relevant words: proxy, reverse proxy
#### category: software development
#### scope: medium,expert

## Word: Revers Proxy
### Description:
Reverse proxy sits between internet and the website(or webserver hosting target website), intercepts the requests sent by client and processes them before forwarding those requests to web servers. A reverse proxy is used to hide the ip address of the web server hosting the target website behind a domain name. For example, google.com is the domain name that is shown to us instead of ip address of the server hosting the google website because of reverse proxy.
A simple flow of a web request with reverse proxy will be as follows:
internet -> reverse proxy -> website(webserver hosting the website)
#### search keywords: proxy, reverse proxy
#### relevant words: proxy, forward proxy
#### category: software development
#### scope: medium,expert

## Word: Indexing
### Description:
In computer programming, indexing is the process of saving the data into virtual data structures in RAM/in-memory storage. For example, if we load a csv file into a list in java, we shall be indexing the csv data.
#### search keywords: indexing, index
#### relevant words: 
#### category: software development
#### scope: medium,expert

## Word: DNS
### Description:
DNS(domain name system) acts as phonebook of internet. It translate domain names to IP addresses and vice versa for identification. For example domain "google.com" has IP address "142.250.181.174" associated with it. DNS converts IP addresses to domain names so that they can be accessed by browsers for easy human accessibility as humans search with domain names rather than complex numbers(e.g IP address).
#### search keywords: dns, domain name system domain system
#### relevant words: ip address, rir
#### category: computer networks
#### scope: expert

