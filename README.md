# Database of Clause Linkage Constructions in Australian Languages (CLAusLink)

Welcome to CLAusLink, a database of clause linkage constructions from a representative sample of 75 Australian languages (Pama–Nyungan, non-Pama–Nyungan, and Kriol). This serves as the accompaniment to the thesis *Clause linkage in Australian languages: A typological study*. An introduction to the database is given in Chapter 2 §4.

The aim of the database is to serve as a link between the typology and the data that it draws from. It consists of a long list of constructions differentiated by morphosyntactic type and functional domains, and they are annotated with features explored in the thesis (e.g. switch reference marking). Every construction is traceable back to the source material, either through a direct reference, or through examples identified but maybe not well-described. 

The annotations may be somewhat bare for some fields and for some items. More effort was spent on constructions that would have a direct bearing on the thesis content; i.e. conjunctions, non-finite marking, and conditional constructions. However, all entries have a reference, either direct, or through examples. As of April 2023, work on polishing this database is still "in progress".

I will explain how to interpret the columns and rows.


## Rows ##

Every row is a construction (in a loose, non-theoretical sense), and most constructions are of clause linkage. Every construction belongs to a language (the three-letter code) and has source information (reference/example). In theory, these constructions are the result of aggregated observations from the 'Example View' of the database (Ch. 2 §4.1), but that contains direct quoted examples from the sources, and so is not included here.

## Columns ##
`INCL`:	status of sample inclusion: either `sample` or `periph`eral. Peripheral constructions are barely annotated, and should be disregarded.

`LNG`:	language, according to three-letter code. A list of codes is given in `clauslink-sample.csv`. These codes are also occasionally used in the thesis, for example, in Figures 1 and 2 in Chapter 3.

`MS`:	morphosyntactic type.

| MS | category |
| --- | --- |
| cjxCla | clausal conjunction |
| cjxPbo | predicate-bound conjunction |
| int_disc_misc | clause-internal, discourse, miscellaneous |
| indepCla | independent clause constructions |

`r_overview` Contextual overview of marker within construction (with label). Unlike in the constructional schemas, `[X_]` here refers to information in another clause. For example, `[perc_V]:SIMULT` would refer to a 'simultaneous' verb inflection in the presence of a 'perception' verb in the other clause.

`item` Marker, in language.

`gloss`	Author's or my label for the item.

`function_classes` Macro-groupings of functions, grouping together the semantic functions explored in Chapter 3 §3. These are somewhat arbitrary, but reflect some common semantic overlaps; see also Luk & Verstraete (2022).

| class | functions |
| --- | --- |
| t_result_purp | POST-temporal, result, purpose, bound |
| t_prior_cause | PRE-temporal, cause, reason |
| t_simult_circ | CO-temporal, circumsstance |
| compar_manner | comparison, manner |
| cond | condition |
| appreh | apprehension |
| addit | addition |
| disjunct | disjunction |
| contr_advers | contrast, adversative |
| concess | concession |
| complement | complement clause |
| reference | relative clause, nominalisation |

`clacomb_sem`	Contains more detailed information about semantic type. Not consistently filled in.

`notes`	Contains miscellaneous information like etymology, frequency, possibility for insubordination.

`cxn_related`	Contains contextual features that are present in `r_overview` but not in `item` (e.g. deviant case marking, verb type in different clause)

`piv_sens`	pivot sensitive or not. Assume no if empty.

`pro_null`	does construction involve suppression of pronominal indices?

`mainCla_pro`	how are pronouns represented in main clauses? Only filled in for 
IndepCla rows.

`cpxPreds`	nature of complex predication in the language. Assume "symmetrical" if empty.

`locii` Left or right of main clause; also embedding information. This column is presently empty.

`source:`	Direct reference to source (full citation in thesis).

`examples`:	List of examples which show an aspect of that construction. Cited reference is in `[]`, and numbering is in `""`.
