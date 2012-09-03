FERAL
=====

More information on FERAL coming _soon_!

## What is FERAL?

FERAL is a [NodeJS](http://nodejs.org/) framework for development of [RESTful](http://en.wikipedia.org/wiki/Representational_state_transfer) systems.
More broadly, FERAL is an implementation of design guidelines for developing software frameworks which support the implementation of RESTful systems.

The development of FERAL is foremost a research project with the goal of exploring the practical meaning of REST concepts and principles, as well as exploring the possibility of implementing any kind of RESTful architecture using the same framework.
An example of a (mostly) RESTful architecture is the WorldWideWeb.

When finished, FERAL will be usable for implementing RESTful servers and clients, such as services and machine-driven agents, but it will (probably) not be a polished feature-packed development tool.

## Who is developing FERAL?

FERAL is being developed by [Silvia Schreier](http://www.fernuni-hagen.de/dvt/en/team/silvia.schreier.shtml) (University of Hagen) and [Ivan Zuzak](http://ivanzuzak.info) (University of Zagreb).
We are researchers and engineers interested in Web architecture, the REST architectural style and developing models of RESTful systems.
We have published several papers in this area, especially on modeling RESTful systems, and we are using these result as the foundation for FERAL:

* [ArRESTed Development: Guidelines for Designing REST Frameworks](http://www.computer.org/portal/web/csdl/doi/10.1109/MIC.2012.60)
* [A Finite-State Machine Approach for Modeling and Analyzing RESTful Systems](http://www.rintonpress.com/journals/jwe/abstractsJWE10-4.html)
* [Formal Modeling of RESTful Systems Using Finite-State Machines](http://www.springerlink.com/content/j233175h2q3h7631/)
* [Modeling RESTful applications](http://dl.acm.org/citation.cfm?doid=1967428.1967434)

## What is the motivation for developing FERAL?

The idea for creating a framework for developing RESTful systems, rather than Web systems only, grew out of our work on models of RESTful systems.
Furthermore, most existing Web frameworks which claim support for RESTful system development have many drawbacks:

1. disregard for core principles of REST, such as hypermedia, media and link types, application state, code-on-demand, and others.
In contrast, we want to promote these concepts into first-class constructs of the framework.

2. mixing together the concerns of framework developers, technology implementers and application developers, thus increasing development complexity.
In contrast, we want to promote a separation of concerns between these different classes of developers.

3. poor extensibility and reusability as frameworks are often bound to a single technology stack.
In contrast, we want to build a generic framework which can be statically and dynamically extensible with new protocols, media types, code-on-demand engines, and other technologies.

We believe that many of these issues may be solved with generic models of RESTful system which provide an appropriate way to modularize the each system, and in that way promote RESTfulness, separation of concerns and extensibility.
Some recent frameworks, such as [Restfulie](http://restfulie.caelum.com.br/) and [RESTAgent](http://restagent.codeplex.com/), have made excellent progress in this direction.

## What is the current status and expected roadmap for FERAL?

We are currently developing the first prototype of FERAL.
This prototype will implement the core framework modules and will have the implementations of the core Web technologies - the HTTP protocol, the HTML media-type and the URI naming scheme.
However, the first prototype will enable other technologies to be implemented and added.
We plan to have this prototype finished in April 2012.

In the next phases of development we will:

* (April 2012) provide more detail on FERAL and first examples
* (May 2012) refactor and polish the interface definitions for modules based on feedback
* (June 2012) implement code-on-demand engines
* (July 2012) add more existing technologies, such as the ATOM media type, and creating new technologies, such as a JSON media type with links and COD support 

## What is the license for FERAL?

If not stated otherwise, all the materials and code for FERAL are available under the [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0.html).
