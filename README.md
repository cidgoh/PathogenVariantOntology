# Variant Impact Reporting Ontology (VIRO)
The Variant Impact Reporting Ontology (VIRO) is an application ontology for describing pathogen mutations, their functional effects, and links to literature evidence. This will eventually be a slim of [GenEpiO](https://github.com/GenEpiO/genepio); I am currently working on getting the VIRO terms into GenEpiO itself.

The associated data specification can be found at [https://github.com/cidgoh/pathogen-mutation-functionalannotation-package](https://github.com/cidgoh/pathogen-mutation-functionalannotation-package).

For more information about VIRO, please see my thesis: [An ontology-based approach for modelling viral variant functional effects](https://open.library.ubc.ca/soa/cIRcle/collections/ubctheses/24/items/1.0450035).

# Curator Notes

To use Ontofox from the command line, run this line from within ```src/ontology/imports```:

```curl -F file=@"general_ontofox.txt" -o general_import.owl https://ontofox.hegroup.org/service.php```
