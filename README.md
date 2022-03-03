# Timeline

Generating the decision history of council information history as a timeline, to be used to present search results within a temporal context.

Two main approaches to create the timeline
* Identifying the re-use of (near) duplicate documents during multiple council meetings
* Identifying references to (older) documents in the collection

The first approach is based on comparing the document id's, filenames, displaynames and filesizes

The second approach has three sub-approaches where we investigate references of decreasing specificity
1) References by URL (with document/agenda IDs in URL)
2) References by document title
3) References by date (where documents are frequently uploaded on the same date)

Implementation is based on the public council information of the municipality of utrecht
