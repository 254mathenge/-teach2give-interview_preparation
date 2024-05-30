<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents**

- [System Design Primer: The Ultimate Guide](#system-design-primer-the-ultimate-guide)
  - [Need for the System Design?](#need-for-the-system-design)
  - [Design Methods in System Design](#design-methods-in-system-design)
    - [1.Architectural Design](#1architectural-design)
    - [2.ERD Diagram](#2erd-diagram)
    - [3.UML Diagram](#3uml-diagram)
    - [4. Class Diagrams](#4-class-diagrams)
    - [5.Sequence Diagrams](#5sequence-diagrams)
  - [System Design Concepts](#system-design-concepts)
    - [1.Performance vs Scalability](#1performance-vs-scalability)
      - [Performance:](#performance)
      - [Scalability:](#scalability)
    - [2.Latency vs Throughput](#2latency-vs-throughput)
      - [Latency:](#latency)
      - [Throughput:](#throughput)
    - [3.Consistency Patterns and Availability Patterns](#3consistency-patterns-and-availability-patterns)
      - [Consistency:](#consistency)
      - [Availability:](#availability)
  - [Advanced Concepts in System Design](#advanced-concepts-in-system-design)
    - [1.CDN-Content Delivery Network .](#1cdn-content-delivery-network-)
    - [2.DNS-Domain Name System](#2dns-domain-name-system)
    - [3.Caching](#3caching)
    - [4. Proxies](#4-proxies)
  - [Components of System Design](#components-of-system-design)
    - [1.Microservices and Service Discovery](#1microservices-and-service-discovery)
    - [2. Database Systems:](#2-database-systems)
      - [RDBMS](#rdbms)
        - [Characteristics](#characteristics)
      - [NoSQL](#nosql)
        - [Characteristics](#characteristics-1)
    - [3.Communication Protocols](#3communication-protocols)
      - [Various communication protocols.](#various-communication-protocols)
  - [Approaching System Design Interview Questions](#approaching-system-design-interview-questions)
    - [Step-by-step Guide](#step-by-step-guide)
      - [1.Requirements clarification](#1requirements-clarification)
      - [2.Estimation of resources](#2estimation-of-resources)
      - [3. System interface definition](#3-system-interface-definition)
      - [4.Defining Data model](#4defining-data-model)
      - [5.High-level design](#5high-level-design)
      - [6.Detailed design](#6detailed-design)
      - [7.Identifying and resolving bottlenecks](#7identifying-and-resolving-bottlenecks)
  - [Sample System Design Interview Questions and Solutions](#sample-system-design-interview-questions-and-solutions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# System Design Primer: The Ultimate Guide

It is a step-by-step process of defining a particular software's architecture, modules, components, etc.

Tech giant companies they check the interviewer's ability to think about building the application's architecture from scratch.

This system design primer helps you to understand the essence of system design and various concepts from basic to advanced.

## Need for the System Design?

It prepares the architecture of the software or application.

Enables you decide whether you want to use SQL or NoSQL databases based on the data you need to store

Enables you decide how to make the application scalable in case the traffic increases.

## Design Methods in System Design

### 1.Architectural Design

Describes the infrastructure, model, view, components, and interaction.

### 2.ERD Diagram

Designs the application's database structure.

### 3.UML Diagram

It is used to prepare modeling software systems.

### 4. Class Diagrams

Provides an overview of the system's data and functionality.

### 5.Sequence Diagrams

Represent the interaction between the various components of the system.

## System Design Concepts

### 1.Performance vs Scalability

#### Performance:

It is when a website or application serve resources faster.

#### Scalability:

Ability to scale the application.Eg. If Your pplication is becoming more popular every day, and due to that, your application’s server is getting more requests. Now, how do you handle it?

### 2.Latency vs Throughput

#### Latency:

Network delay that occurs due to Geographical distance, transport protocol, or network infrastructure.

#### Throughput:

Number of operations the system can handle in a particular time

### 3.Consistency Patterns and Availability Patterns

#### Consistency:

Consistency ensures that all nodes in the system read the same data at a particular time.

#### Availability:

Ensures that each request receives a response either with fresh or old data.

## Advanced Concepts in System Design

### 1.CDN-Content Delivery Network .

It is a distributed server network located at different geo-locations.

Used to deliver content like images, various data,from the server by reducing latency and delivers the resource faster

### 2.DNS-Domain Name System

Allows users to access the website and its resources using their unique and unique domain name
(e.g., www.example.com).

### 3.Caching

Serve resources faster between the web application and the source of the data..

### 4. Proxies

Works between the client of the application and the internet.

Whenever you request to get resources from the internet, the application requests the proxy server, and the proxy server gets resources and sends them back to the application.

## Components of System Design

### 1.Microservices and Service Discovery

The microservices break down complex applications into small services, such that each service works independently and accomplishes specific tasks.

### 2. Database Systems:

#### RDBMS

When you need to store structured data, you can choose the RDBMS for the software or application.

##### Characteristics

  <ul>
  <li>It stores the data in the table format.</li>
  <li>SQL is a query language for the RDBMS databases.</li>
  <li>Accessing data from the RDBMS database is slow</li>
  </ul>

#### NoSQL

It stores the data in the key-value pair instead of in table format.

##### Characteristics

  <ul>
  <li>It stores the data in the key-value pair format.</li>
  <li>Each record can contain different key-value pairs.</li>
  <li>It is faster than RDBMS databases</li>
  </ul>

### 3.Communication Protocols

Refers to the rules to communicate or exchange the data between two systems.

#### Various communication protocols.

<b>HTTP/HTTPS- hypertext transfer protocol</b>:They are used in web-based communication.
<b>TCP/IP-transmission control protocol</b>:used to communicate over the internet.
<b>UDP- user datagram protocol</b>:It is mainly used for live streaming.
<b>WebSockets</b>: It builds the connection between two web applications.

## Approaching System Design Interview Questions

### Step-by-step Guide

#### 1.Requirements clarification

**Function requirements:**Requirements in the application witwhich user interacts.

**Non-function requirements:**
Requirements to improve the application's capabilities.

#### 2.Estimation of resources

Deciding what kind of resources you should use.

#### 3. System interface definition

Defining the API endpoints and what to expect from each API endpoint.

#### 4.Defining Data model

Selecting a database for the application.Eg.relational databaseand No SQL

#### 5.High-level design

Designing the high-level components.

#### 6.Detailed design

Analyze the system to fulfill the non-functional requirements.

#### 7.Identifying and resolving bottlenecks

Identify the bottlenecks in your system design and discuss the solutions to resolve them with the interviewer.

## Sample System Design Interview Questions and Solutions

  <ol>
 <li>How would you design a URL Shortening service similar to TinyURL?</li>
 <li>How would you design a Web Crawler?</li>
 <li>How would you design Facebook and Instagram?</li>
 <li>4. How would you design the API rate limit?</li>
