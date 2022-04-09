# CodeQ.Taggr
A Neos.io package to tag nodes for internal management.
For example you can create a tag called "needs review" to tell
other editors, that the document or content node needs additional review.

## Usage

To enable the tagging on nodes, just add `CodeQ.Taggr:Mixin.Taggable`
to the document or content nodes you wish to be taggable.

Then you create a document node of type `CodeQ.Taggr:Document.Tags`,
labeled as "Tags" and add tag document nodes to it. Now you can go to your
taggable nodes and tag them. When you navigate to the tag in your inspector
you will see a list of all nodes that are tagged with it.
