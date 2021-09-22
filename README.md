# the way we thought on metadata

A catalogue of metadata elements used in a number of services, and the
*how*s and the *why*s behind them.

I use past tense *thought* rather than *think* since the thinking
actually took place about a decade ago. I hope these docs will make
reuse of metadata and content, created in the past, easier. Basically
we need to understand how we reasoned then.

The element I refer to is not an element as in an XML element or a SQL
column. It is the semantics.

Having said that, whenever I have started to figure out how we did
with an element, I run into the questions:

 **How did we store that in the databases**
 **How did the curators create those data**
 **How did we index them for the users**
 
## base metadata categories and semantics

The table below is from Weibel et al (1998). This is the fifteen DCMI
elements from RFC2413. The later versions omits this table which shows
how metadata elements are related to each other and how they help
users find relevant information.

|[Content](content/README.md)|[Intellectual Property](intellectual-property/README.md)|[Instantiation](instantiation/README.md)|
| ------------ |:--------------------- |:------------- |
| [Title](content/README.md#title)|[Creator](intellectual-property/README.md#creator)|[Date](instantiation/README.md#date)|
| [Subject](content/README.md#subject)|[Publisher](intellectual-property/README.md#publisher)|[Format](instantiation/README.md#format)|
| [Description](content/README.md#description)|[Contributor](intellectual-property/README.md#contributor)|[Identifier](instantiation/README.md#identifier)    |
| [Type](content/README.md#type)|[Rights](intellectual-property/README.md#rights)|[Language](instantiation/README.md#language)|
| [Source](content/README.md#source)|
| [Relation](content/README.md#relation)|
| [Coverage](content/README.md#coverage)|

This text follow the vocabulary of Powell et al (2007) in the DCMI
Abstract Model which is inspired by the RDF way. I think in that way,
but I have to confess that I have never implemented RDF the past
twenty years (I used RDF when it was new late in 1990ties and my
conclusion was that it is the best way to envision a metadata system,
a tool for stringent thinking. However, I felt that it is far too complicated
for using at a practical level.)

The metadata elements used for discovery are a part of a service user
interface. Lagoze (1997) gives a discussion of how the role of the
*description set* at the cognitive level in information retrieval. The
*description set*s are usually what is presented to a user at search
time in the result set. These sets comprises multiple property-value
pairs that together form a surrogate to the user which is what he or
she can use for evaluating or assessing a resource's suitability. The
task for the user is to evaluate query agains the result set,
candidate description sets and finally retrieve the resource.



## References

DCMI Usage Board (2020). DCMI Metadata Terms  - https://www.dublincore.org/specifications/dublin-core/dcmi-terms/

Klyne, Graham and Jeremy Carroll, editors (2004). Resource Description Framework: Concepts and Abstract Syntax. W3C Recommendation. -
 http://www.w3.org/TR/rdf-concepts/

Lagoze, Carl (1997). From Static to Dynamic Surrogates: Resource Discovery in the Digital Age - *DLib Magazine* -
http://www.dlib.org/dlib/june97/06lagoze.html

Powell, Andy, Mikael Nilsson, Ambjörn Naeve, Pete Johnston and Tom Baker (2007). DCMI Abstract Model - https://www.dublincore.org/specifications/dublin-core/abstract-model/

Weibel, S., J. Kunze, C. Lagoze and M. Wolf (1998). Dublin Core Metadata for Resource Discovery. RFC2413 -
https://datatracker.ietf.org/doc/html/rfc2413
                                                   














