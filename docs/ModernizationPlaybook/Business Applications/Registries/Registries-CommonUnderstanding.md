---
layout: default
grand_parent: Business Applications
parent: Registries
title: A Common Understanding
nav_order: 1
---

# Registries

**Archetype: Registries**

## A Common Understanding

<img align="center" src="assets/images/RegistriesConcept.png" width="720" height="325"/>
With over 100 "registries" in the current application inventory, there appears to be a broad and varied concept of what is a registry.  At a fundamental level, a registry is where someone keeps track of things.  From the application inventory, it appears that "the thing" can be any of:
- training courses, 
- people and their contact information, 
- "people who have registered" for a program or service, 
- an event associated with a person (a birth, or a marriage, for example),
- a will,
- a person with a unique privilege, like a lobbyist,
- a person with a hunting license,
- a business and information about that business,
- information about protected areas in B.C.,
- a bridge,
- early childhood educators,
- a piece of land and its boundaries,
- title to a particular piece of land,
- public entities that trade carbon credits,
- and more.

Efforts are underway in the OCIO to recognize a set of very import things that the B.C. Government keeps track of, and to treat those things in special ways.  Most of the items in the above list will fit into this set somewhere.  That set of very important things currently looks like this:

<img align="center" src="assets/images/Registries-7OfHighestOrder.png" width="720" height="325"/>

The Entitlements Registry is currently under consideration, and may be a generalisation of things like Land Titles.  We are working to refine the set of "high order" registries.  Other examples of entitlements might be: 
- permission to fish in a waterway, 
- a license to operate a particular type of business
- a certificate that allows a person to teach in B.C.
- perhaps, a Court Order
- certification of an Emergency Medical Assistant
- over-sized vehicle permits, with accompanying restrictions
- permission to be prescribed restricted medications

Together, these may be considered Master Data sets of the highest order.  There are other important data sets that we must treat in special ways, but these are considered the critical ones.  If we get information about any of these things wrong, then we're not doing good government, let alone digital government. 

The nature of a registry embodies qualities of authority, reliability, unquestionable integrity, consistency, and timeliness.  Each registry holds raw - not derived - data that is the unequivocal source.  And there is exactly one registry of record for each kind of data.  As a general rule, registries are not duplicated.  Changes are always made to registry records via a consistent single procedure (an API, for example).   Access to its data is facilitated by procedures owned by the registry, itself.

As an example, government needs to keep track of information about people.  There should be one place to go - the People Registry - to get or update information about people, about a person.  There should be only one place considered the Registry of Record, which holds the definitive, authoritative, current information about a person.  No other list, spreadsheet, database, or extract, can be considered definitive. Update of a person's data should happen nowhere else.  So access to the Registry of Record must be made easy for all other systems that require information about people.  Other systems that refer to a person in the People Registry will use not a person's name, but a key, a pointer (that is not an existing personal identifier like a PHN or a PEN), which provides an abstraction, and thus a further element of protection.

The B.C. Government work on Data Registers has borrowed from the excellent work of the UK Government, and offers the following characteristics of a registry (subject to refinement): 
- there is a single register for each subject
- only data relevant to the subject is stored in it
- a registry contains only raw data, and nothing that is derived
- a registry uses common standard names to refer to its data
- a registry is always kept up to date by systems, not humans
- appropriate governance and ownership are in place for each 
- data in a registry is reliably the most current
- each one is declared open, shared, or private
- each is the authoritative source
- history is maintained for each record
- a record can never be lost or removed - history is maintained
- each has a named owner
- the existence of a register can be linked to a driver based in law, policy, or ministry mandate

There are also registries in government that may not meet the "highest order" benchmark.  But their governance and the approach to their integrity should follow similar diligence as those deemed most important to good government.