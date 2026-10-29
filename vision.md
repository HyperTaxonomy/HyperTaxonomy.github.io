---
title: Vision
nav_order: 2
---

# A web of concepts

**Why HyperTaxonomy exists, and what it could become.**
{: .fs-6 .fw-300 }

## Meaning lives in connections

In Genesis, the first task given to the first human is to name the animals.
Naming is where taxonomy begins, but names alone are not language. Human
language is not remarkable for the number of its words. It is remarkable
because it is generative: a finite set of words, and rules for combining them,
can produce an unlimited number of meanings, including ones nobody has
expressed before. That generativity comes from the fact that words don't carry
meaning on their own. *Bank* means one thing next to *river* and another next
to *loan*. Linguists observed a century ago that a word is defined by its place
among other words. Neuroscience paints a similar picture: a concept is not
stored in a single cell but in a pattern of connections.

The neural network model puts this in formal terms. Each node is simple. What
the network knows lives in how the nodes are connected: which ones, how many,
and in what way.

Hypertext gave us connections on a planetary scale, and changed how humanity
stores knowledge, does research, and finds its way around the world. But most
of those connections carry no meaning that another system can rely on. A link
can be explained by the text around it, and a few attributes, such as `rel`,
tell a browser or a crawler something about it. Yet there is no universal,
interoperable way for a link to say "this is a kind of that," "this is the same
thing as that," or "this is defined there."

That was the promise of the Semantic Web. Its standards exist and work well:
RDF, OWL, and SKOS power library catalogs, museum collections, and knowledge
bases like Wikidata. But they never reached most of the web. Publishing linked
data asked ordinary authors for expertise and effort they had little reason to
invest, so structured meaning stayed in an archipelago of specialist datasets.
The web is a network of *pages*. It is not yet a network of *concepts*.

## The tag is the seed

Almost every content system already has a primitive that comes close to being a
concept: the tag, category, or term. It names an idea that recurs across
content. But it is trapped in three ways.

1. **It is a label, not an identity.** Two sites' "Dog" tags are unrelated
   strings. So are "Dog" and "Canis familiaris" on the same site.
2. **It lives in at most one tree.** A hierarchical term can have only one
   parent, so it can be organized from just one point of view.
3. **It cannot see past its own site.** Whatever it means, it means only
   locally.

HyperTaxonomy starts from a simple premise: release the term from these three
traps, and it becomes a node in a network of meaning. This approaches the
Semantic Web's goal from the other end. Instead of asking authors to learn new
formalisms, it starts from something they already do every day — tagging their
content — and builds the structure from there. Where it meets the Semantic Web,
it speaks the same standards, rather than inventing new ones.

## A hierarchy is an answer to a question

Every hierarchy is built on a criterion, and it is only meaningful if it
applies that criterion consistently at every level. *Mammals → Canines → Dog*
answers the question "what is it descended from?" *Service animals → Dog*
answers "what work does it do?" *Pets requiring vaccination → Dog* answers "how
must it be cared for?" All three are correct. None is more true than the
others; they simply answer different questions. Mixing criteria within one tree
destroys its meaning, the way a library would become useless if some shelves
were sorted by subject and others by the color of the cover.

A system that allows only one tree forces one question to win. The others get
dropped, or they get duplicate terms: a second "Dog" for service animals, a
third for vaccination schedules, each one disconnected from the rest.

HyperTaxonomy lets one concept take part in any number of structures, each
keeping its own criterion intact. The model is deliberately hybrid. Within a
hierarchy, where every level follows the same criterion, connections are
transitive by design: placing *Dog* among *Canines* brings every dog breed
along with it, because a breed of dog is still a dog. At the same time, it is
possible to define only a subset containing particular breeds (subbranches) as
service animals, and yet another subset as legal pets.

This is where generativity returns. Once a concept sits in several hierarchies,
they intersect. "Service animals that need vaccination, near me" is a set
nobody curated by hand. It emerges from connections that were each made for a
different reason. A finite set of terms and relationships answers an open-ended
set of questions, in the same way a finite vocabulary produces open-ended
speech. And *inclusion* is only one verb in this grammar. Site owners can
define their own relationship types to express whatever connections their
subject needs.

## What a concept means

How do we know what a term means? There are four ways, and a well-anchored
concept may use all of them:

- **Context:** the content it is attached to.
- **Definition:** an explicit description of what it is.
- **Identity:** a stable reference to the same concept elsewhere, so that two
  labels can be recognized as one idea.
- **Equivalence:** its local synonyms, translations, or the names it goes by in
  other communities.

The definition does not have to be written locally. A site can delegate it:
point a term to an authority that already maintains the concept, and let the
term follow that authority as it evolves. Delegation also works at a larger
scale: a whole vocabulary of related terms, together with the relationships
between them, can be delegated to the site that knows that domain best.

Identity is what makes a network out of separate vocabularies. Once two sites'
terms point to the same identifier, they are recognized as the same concept,
whatever each site calls it and in whatever language. Every connection between
sites ultimately rests on that recognition.

## Authority without a center

Wikipedia is the obvious authority for general concepts, and it is invaluable.
Yet by design it cannot cover everything. Its notability rules exclude the rare
breed, the regional dialect word, the internal term of a small profession:
concepts that matter enormously within a narrow domain. Those concepts already
have their own authorities. They are scattered across specialized sites, each
of them the best source for one narrow thing.

There is a deeper reason not to rely on one authority, however good. Any
central source has a point of view: what counts as notable, how a topic is
framed, which of several competing definitions is presented as canonical. If
you concentrate the web's vocabulary in one place, you concentrate its biases
too.

So authority in this network is granular and chosen. It can be assigned concept
by concept, to whoever knows that concept best, by the site that needs it. And
the network is *decentralized*, not *federated*. Federation asks every
participant to adopt the same technology and follow the same rules.
Decentralization asks only for a common interface. No node is in charge of the
vocabulary, and no node needs to know about another before linking to it.
*Connecting* is not *conforming*: each site keeps full control over its own
terms, its own hierarchies, and its own choice of whom to trust.

## A network of networks

Put these pieces together and they add up to more than a better way to organize
one site. They are the foundation of a single neural network of concepts,
spanning sites and systems, that no one owns and every participant helps build.

Inside a site, terms connect to each other through typed relationships and
parallel hierarchies, forming a local network with its own specialization.
Between sites, terms connect through shared identities, delegated definitions,
and links, forming pathways from one region of knowledge to another. Each
region stays autonomous: it decides what its concepts mean, how they are
organized, and which other regions to connect to. No region is in command of
the whole, and the whole does not depend on any one region.

The network grows through use. A connection appears because someone needed it.
This is how the original web grew, one link at a time, added by whoever found
it useful, without a central plan.

It also changes how things are found. Directories, search engines, and AI
assistants all rely heavily on existing authority: link counts, clicks,
citations. That favors what is already established, and creates a
chicken-and-egg problem for anything new. In a network of concepts, a post
published today has no backlinks, but if it is attached to a well-connected
concept, it can be reached immediately from every site connected to that
concept. It is found because of what it is *about*, not because of how
*popular* it already is.

## Explicit and implicit

Large language models are neural networks too, but of a different kind. They
absorb concepts from vast amounts of text, and what they learn is implicit:
spread across billions of parameters, impossible to point to, attribute, or
correct directly.

A network of linked concepts keeps its knowledge in the open. Every connection
is explicit, made by a known author for a stated reason, and can be inspected,
disputed, and fixed. The two complement each other. An explicit network gives
machines something they lack: a map of meaning drawn deliberately by people,
with sources. And because the network is published in open, machine-readable
formats, any agent can traverse it.

## Beyond WordPress

The HyperTaxonomy Suite runs on WordPress because that is where a large share
of the web's human-written content already lives, along with the terms that
organize it. It has no prerequisites: WordPress is all you need. It is
certainly our hope that, as HyperTaxonomy gains popularity, the web will become
better organized and more coherent.

But the ideas are not tied to WordPress. Typed relationships between terms,
overlapping hierarchies, delegated identity, and links between sites can exist
on any platform that publishes content. Nothing in the design of HyperTaxonomy
or TermConnect is specific to WordPress; only the platform layer would need
rewriting. That work simply hasn't been done yet.

The web succeeded because anyone could implement its protocols. A network of
concepts can succeed the same way, but only if it is not confined to one
platform. The suite is open source, and this is an open invitation: take it,
port it, and let other systems join the network. The code is on
[GitHub](https://github.com/HyperTaxonomy).

The first taxonomy began with naming things. The next level connects the names.
