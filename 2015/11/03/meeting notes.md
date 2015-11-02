# Note:
## Michael's side:

* add original scopeId in the document;

## Stanley's side:
* Change the current process to export the documents to two parts: one is the document change, and the other is document remove;
* Extract the original scopeId from the document;
* Change the current document format to CSV, columns: 
1. change event: attributeid, scope, scope id, sha encode, value;
2. remove event: attributeid, scope, sha encode

