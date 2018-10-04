# kg-data
This repository contains two knowledge graph datasets: NATION and UMLS. 

- NATION contains relations between countries and consists of 14 entities(countries) and 56 relations.
- UMLS is a biomedical ontology dataset and consists of 135 entities and 49 relations.

Both dataset consist of three tab-seperated files:

- `entities.txt`: List of entities, formatted as `entity_id \tab entity_name`

- `relations.txt`: List of relations, formatted as `relation_id \tab relation_name`

- `triples.txt`: List of known facts, formatted as `relation_id \tab entity_id1 \tab entity_id2`

  - means `entity_id1` has `relation_id` relation with `entity_id2` 

Both entity-id and relation-id start from 0.

Additionally, UMLS dataset contains one more file: `entity_category.txt`, which contains a group name of each entity in UMLS data,
and formatted as `entity_id \tab entity_category`.

# Why Knowledge Graphs Are Foundational to Artificial Intelligence
AI is poised to drive the next wave of technological disruption across industries. Like previous technology revolutions in Web and mobile, however, there will be huge dividends for those organizations who can harness this technology for competitive advantage.

I spend a lot of time working with customers, many of whom are investing significant time and effort  in building AI applications for this very reason. From the outside, these applications couldn’t be more diverse – fraud detection, retail recommendation engines, knowledge sharing – but I see a sweeping opportunity across the board: context.

Without context (who the user is, what they are searching for, what similar users have searched for in the past, and how all these connections play together) these AI applications may never reach their full potential. Context is data, and as a data geek, that is profoundly exciting.

We’re now looking at things, not strings

The best example of the value of context within data is the consumer Web. For example, most of us interact with Google every day. To understand the value of context in AI better, let’s look back to 2012, when Google fundamentally transformed search from “strings” to “things.”

Google is a clear leader in the field of AI through its own innovation and strategic acquisition, not least of which was its acquisition of AI firm DeepMind in 2014. But a smaller, lesser publicized move, I believe, deserves more attention: In 2012, Google introduced its “Knowledge Graph.”

Before the Knowledge Graph, searching via Google was a “string.” If I wanted to know when “Star Wars: The Last Jedi” was playing, I had to search for a movie theatre, then click through to find the right movie and then find and scroll through the showtimes. I had to hop across multiple links.

for more info about knowledge Graphs checkout the following links:
*https://www.datanami.com/2018/03/20/why-knowledge-graphs-are-foundational-to-artificial-intelligence/
*https://paul4innovating.com/2017/12/29/as-we-enter-2018-we-will-need-knowledge-graphs/

for info about the py2neo and neo4j:
*https://medium.com/neo4j/py2neo-v4-2bedc8afef2
*https://neo4j.com/graphacademy/
