
`//Bibliographic Record\\`

Structured description of a doc/item in a lib DB or catalogue.

- Identifies a doc
- Bibliographic control
- Describes its feature
- Helps users locate & access info resources
- Also called metadata or a surrogate record
- Modern records follow standards like MARC
- Uses cataloguing rules (AACR2/RDA)

> Important Standards
  - MARC
  - AACR2
  - RDA
  - ISBD

`Structure`
TEPPSNS

> Title Area `Title : Subtitle / Statement of responsibility`
  Statement of responsibility (author/editor)
   2 auth: join using and
   3 or more: Names written in the order shown on title page
   Editors: use arrv ed. or eds.
   Coporate Author: Org name 

   AACR2 old rule
    if 3 or more authors: first author + [et al.] 
    eg: / R. Sharma ... [et al.]

   RDA Modern practice
    all authors if possible

> Edition Area `. — Edition statement`
> Publication Area `. — Place : Publisher, Year`
> Physical Description Area `. — Pages : Illustrations ; Size`
> Series Area `.-(Series title)`
> Notes Area `. — Note`
> Standard Number Area `. — ISBN/ISSN`


Real-World Example

1. Descriptive Areas (In Exact Order)
The Great Gatsby : a novel / by F. Scott Fitzgerald. — 2nd ed. — New York : Scribner, 2004. — 180 p. : ill. ; 21 cm. — (Scribner classics). — Includes bibliographical references. — ISBN 9780743273565.

2. Access Points (Appended at the Bottom)
Author Entry: Fitzgerald, F. Scott (Francis Scott), 1896-1940.Subject Headings: Long Island (N.Y.) — Fiction. ; Wealth — Moral and ethical aspects — Fiction.Keywords: Jazz Age, Roaring Twenties, Jay Gatsby, American Dream.


- Space-Dash-Space Rule
  The standard separator between areas
  . —
  (period + space + dash)
  This is the key ISBD punctuation feature.




`// MARC - Structure \\`
 Standard format for storing bibliographic data in machine-readable form

 Structure

 1. Leader
   - Fixed length field - 00 to 23 (24)
   - contains record control info
 2. Directory
   - Gives location of fields in record
   - 12 char (tag-3, field length-4, Starting position-5)
 3. Variable Fields
   > Control Fields (00X)
    - Fixed data
    - Eg: 001, 005, 008
   > Data Fields (01X to 8XX)
    - Bibliographic Information
    - Divided into:
      Tag : 100-author, 245-title, 300-phy desc
      Indicators: 2 char positions
      Subfields: smallest unit of info. preceded by delimiter symbols like $ or ‡
 
 > Important MARC tags
  - Control Fields (00X)
     001	Control number
     005	Date & time of latest transaction
     008	Fixed-length data elements
 
  - Main tags
     020    ISBN
     082    DDC Number
     100    Main author/Personal Name
     110    Corporate Author
     245    Title
     246    Variant Title
     250    Edition
     300    Physical Description
     500    General Note
     504    Bibliography note
     650    Subject Heading
     700    Added Entry
     740    Added Title Entry




`// AACR2 - Structure \\`
 Catalogue code for preparing bibliographic records

 Structure

 > Part 1 - Description
   Covers physical/bibliographic description
   1. Title & statement of responsibility
   2. Edition
   3. Material or type of publication specific details 
   4. Publication details
   5. Physical description
   6. Series
   7. Notes
   8. Standard Number & terms of availability

 > Part 2 - Headings & Access Points
   1. Main Entries
   2. Author headings
   3. Subject access
   4. Uniform titles
   5. Cross references
   6. Added entries/Access points



`// RDA - Structure \\`
 Modern cataloguing standard replacing AACR2

 Structure
  - Based on FRBR model
 
> Main Entities:
- Work: Distinct intellectual or artistic creation (eg: William Shakespeare's idea for Hamlet)

- Expression: Specific intellectual or artistic realization or language form of a work
 (eg: og English text vs German translation)

- Manifestation: Physical embodiment
  (Paperback printed edition by a specific publisher)

- Item: Single exmeplar of manifestation (the exact copy sitting on a specific library shelf with a barcode)

> Main Components:
- Attributes of Resources: Charcterizing deatils of entity 
   Eg: Work has title; Manifestation has ISBN

- Relationships Among Entities: Semantic links that tie the entities together
   Eg: this expression 'is realized through' that work

- Access Points: Formatted strings used to retrieve the entities during searches

> Organized Into
  Recording attributes: section 1-4 
  Recording relationships: section 5-10

 


`// ISBD - Structure \\`
 International Standard Bibliographic Description

 TEMPPSNS

 Structure
 > 8 Areas
  1. Title & Statement of Responsibility
  2. Edition
  3. Material-specific details
  4. Publication/production/distribution
  5. Physical description
  6. Series
  7. Notes
  8. Standard number & availability

 > Uses Prescribed Punctuations
   . , – : ; / etc.
 


`//Kinds of Bibliographic Files\\`
 1. Author File: arranged by author name
    eg: Books by ranganathan
 2. Title File: Arranged alphabetically
 3. Subject File: Arranged by subject headings/class numbers
    eg: subject wise order
 4. Union Catalogue File: Combined catalogue records from libs
 5. Serials File: Records of journals, mags, NPs, serail pubs
 6. Authority File: standard forms of names, subs, titles
 7. Classified File: arranged according to class scheme
    eg: ddc, cc
 8. Holdings file
 9. Machine-readable Biblio file in MARC, XML format
 10. Online biblio database
    





`//  FRBR - Functional Requirement for Bibliographic Control \\`
 
 Conceptual model for organizing biblio info 
 1998
 IFLA

 Improves biblio retrieval
 Show relationships among resources
 Meet user needs efficiently

 Basis of modern cataloguing
 SUpports digi libs
 Improves OPAC navigation
 Foundation for RDA

> User tasks in FRBR
 1. Find
 2. Identify
 3. Select
 4. Obtain

> FRBR Entity Groups
 - Group 1 Entities (WEMI Model)
 1. Work
 2. Expression
 3. Manifestation
 4. Item

 - Group 2 Entities
 Responsible for creation/production
 1. Person
 2. Family
 3. Corporate Body

 - Group 3 Entities
 Subjects of works
 1. Concept
 2. Object
 3. Event
 4. Place
 




`// Library Catalogue \\`
 
 Catalogue is a “finding list” of library materials
  - Charles cutter

> Types of Library Catalogue

- By Form
  Book catalogue
  Card catalogue
  Sheaf catalogue
  OPAC

- By Arrangement
  Author catalogue
  Title catalogue
  Subject catalogue
  Classified catalogue




`// Classified Catalogue \\`

- Logical/Systematic arrangement by class numbers
- Two parts: Classed part + Alphabetical Index
- Difficult for ordinary users; index neede first
- Related subjects kept together
- Depends on classi scheme (DDC, CC, UDC)
- Subject approach
- Better for subject browsing
- Requires knowledge of classification
Eg: 500-Science, Maths-510, Astronomy-520



`// Dictionary Catalogue \\`

- Alphabetical arrangement
- Single unified alphabetical file
- easy and direct to use
- Related subjects scattered alphabetically
- Depends on subject headings list (SEARS, LCSH)
- Alphabetical approach
- Better for known-item search
- No special knowledge required




`// Bibliographic Description \\`
 Systematic description of a doc to identify and distinguish it from other

 Based on standards such as:
  - ISBD
  - AACR2
  - RDA


`// Principles of Description \\`
> AUSSSI CAR
  Accuracy
  Uniformity
  Sufficiency
  Specificity
  Standard Punctuation
  Identification
  Consistency
  Accessibility
  Representation
  








`// Standard Info Retrieval Protocols of Catalogue Systems \\`


`// Z39.50 \\`

 - Standard Client-server protocol for info retrieval & search
 - allows a user in one library system to search and retrieve bibliographic records simultaneously from other library databases worldwide.

 Maintenance: LC

 1988 - 1st Version
 2003 - Latest major revision

  > Standard: 
    ANSI/NISO Z39.50
    ISO 23950

  > Search Syntax
    Uses Bib-1 Attribute Set
  

`// ZING \\`
  Z39.50 International Next Generation
  To modernize old Z39.50 protocol
  Adapt to web technologies



`// Successors of Z39.50 \\`

   Output format of SRU/SRW: XML

   For Live, complex catalog queries

  >//// SRU ////<
    Search/Retrieve via URL

    Uses standard internet URLs to send search requests and returns results using XML.
    
    REST-based
    Uses HTTP
    Query in URL
    Returns XML

  >//// SRU ////<
    Search/Retrieve Web Service

    Same as SRU; more structured web service protocols (SOAP)

    SOAP Based
    Uses HTTP + SOAP
    Returns XML




`// Alternatives of Z39.50 \\`
 
 >// OAI-PMH //<
   Open Archives Initiative Protocol for Metadat Harvesting

   For Bulk data harvesting
 

 >// SPARQL //<
   SPARQL Protocol and RDF Query Language

   Querying RDF Data
   Semantic Web
   Linked data

   Official Port Number: 210


  >// RESTful APIs with JSON //<
    Representational State Transfer
    Faster and easier to integrate than binary Z39.50 streams

    For application development
    returns JSON / XML format


  >// GraphQL //<
    Allows clients to request exactly the metadata fields they need.
    Reduces bandwidth & prevent over-fetching





`// Bibliographic Record Formats \\`
 
 Standardized structures used for storing, organizing, exchanging, and retrieving bibliographic information in manual and automated library systems.

> Traditional/Library Automation Formats
  ISO 2709
  MARC
  MARC 21 
  UNIMARC
  CCF

> Digital Matadata/ Web Formats
  Dublin Core
  MODS
  METS
  BIBFRAME
  RDF


`\\ ISO 2709 //`
 International Standard for machine-readable biblio record structure

 Standardizes exchange of bibliographic records
 Supports library automation
 Basis of MARC Formats

 Dev in 1960s
 By Henriette Avram, Library of Congress
 Earlier STandard: ANSI/NISO Z39.2
 Current Standard: ISO 2709:2008

 Imp Encodings:
  MARC-8
  UTF-8/Unicode

 Structure
  Leader
  Directory
  Variable Fields
   Control Fields
   Data Fields



`\\ MARC 21 //`
  Modern International version of MARC

  Based on ANSI/NISO Standard Z39.2

  Improves compatibility among Integrated Library Systems (ILS)

  Created by combining:
   USMARC, CANMARC

  > 5 Major Data Formats
   1. Bibliographic Format: For Cataloguing books, journals
   2. Authority Format: Authorized names, subjects, headings
   3. Holdings format: copy/location info
   4. COmmunity Info Format: Community resource info
   5. Classification Data Format: Classi no & schemes  

  Supports 2 encoding systems
   1. Marc-8
       Based on ISO 2022
       Supports scripts like:
        Hebrew, Cyrillic, Arabic, Greek, East Asian Scripts

   2. UTF-8 Unicode
       Supports:
        Almost all world languages supported by unicode





`\\ UNIMARC //`
  Universal MARC Format developed by IFLA
  Inernational Exchange

  3 Main structural parts
   1. Record Label (Leader)
   2. Directory
   3. Variable Fields


`\\ CCF //`
  Common Communication Format
  Standard bibliographic exchange format for information agencies and libraries.
  By UNESCO

  Editions: CCF/B and CCF/F
  Based on ISO 2709
  
  Developed due lack of copatibity among formats

  > Components:
  1. Record Label - Fixed length (24 Characters)
  2. Directory - 5 Parts: 
        Field Tag
        Field Length
        Starting Charcter Position
        Segment Identifier
        Occurence Identifier
     
        Unlike ISO 2709 directory entries (12 characters).
         CCF directory entries are 14 characters
         because CCF adds:
          Segment identifier
          Occurrence identifier 
  3. Data Fields
      Indicators
      Subfield Identifiers
      Subfields
      Field Seperator
  4. Record Seperator
       Final character of record

 




`\\ Dublin Core //`
   
   `METADATA STANDARD` used for describing digital and physical resources.

   Contains `15 metadata elements`

   Metadata framework used with Dublin Core  `RDF`

   For web pages, Iages, Videos, E=books, CDs, Digi Repos etc

   Developed by Dublin Core Metadata Initiative(DCMI)
   1995 Dublin, Ohio, USA
   During OCLC/NCSA Metadata Workshop

  > Standards Supporting:
    IETF RFC 5013 : Internet Standard
    ISO 15836-1:2017 : International Standard
    NISO Z39.85 : Metadata Standard

  > Compatiable With:
    XML, RDF, Linked Data, Semantic Web, OAI-PMH

  `DCMI became Independent from OCLC`: 2008


1. Contributor: 
     “An entity responsible for making contributions to the resource.”
2. Coverage: 
     “The spatial or temporal topic of the resource, the spatial applicability of the resource, or the jurisdiction under which the resource is relevant.”
3. Creator: 
     “An entity primarily responsible for making the resource.”
4. Date: 
     “A point or period of time associated with an event in the lifecycle of the
resource.”
5. Description: 
     “An account of the resource.”
6. Format: 
     “The file format, physical medium, or dimensions of the resource.”
7. Identifier: 
     “An unambiguous reference to the resource within a given context.”
8. Language: 
     “A language of the resource.”
9. Publisher: 
     “An entity responsible for making the resource available.”
10. Relation: 
     “A related resource.”
11. Rights: 
     “Information about rights held in and over the resource.”
12. Source: 
     “A related resource from which the described resource is derived.”
13. Subject: 
     “The topic of the resource.”
14. Title: 
     “A name given to the resource.”
15. Type: 
     “The nature or genre of the resource.”



`\\ RDF //`
  Resource Description Framework

  Dev by W3C, 1991

  For representing and exchanging data on the Semantic Web and Linked Data environment.

  - Represent metadata
  - Support Semantic Web
  - Enable Linked Data

  - Used in
     BIBFRAME
     Dublin Core
     Digital Libraries
     Institutional Repos

  RDF is the foundation of Semantic Web

  RDF uses `URI` (Uniform Resource Identifier)

  RDF represents information as: `Triples`
  > Subject → Predicate → Object
    Eg: Book → written by → Author
        Hamlet → created by → Shakespeare

  RDF stores data as: `Nodes + Relationships`

  > Components
   1. Resource:
       Anything Identifiable
       Identified using URI
        Eg: http://example.org/book1

    2. Property (Predicate):
        Defines relationship/attribute
         Eg: hasAuthor

    3. Statement
        Complete RDF Triple




`// METS \\`
  Metadata Encoding and Transmission Standard
   
  `XML based` MD standard
   For encoding descrv, admnstv & structural md of Digi lib

  Hierarchial object representation
  MD packaging

  Dev by
   Digital Library Foundation - initiative
   Library of COngress - Maintenance

  > Designed for:
     Expressing hierarchial structure of digi objects
     Recording names and locations of files
     Recording associated metadata

  NO Vocabulary
  Flexible, Customizable

  `Sections`
   1. METS Header (metsHdr)
       Creator, Editor, Administrative info about METS doc
   2. Descriptive Metadata Section (dmdSec)
   3. Administrative Metadata Section (amdSec)
       Technical MD, RIghts MD, Source MD etc
   4. File Section (fileSec)
       List of files related to digi object
   5. Structural Map (structMap)
       Hierarchial structure of digi object
   6. Structural Links (structLink)
       Records hyperlink between nodes (for web archiving)
   7. Behavioral Section (behaviorSec)
       Associates executable behaviors with content
   



`// MODS \\`
  Metadata Object Description Schema

 - `XML based` bibliographic MD standard scheme
 - Uses XML Schema
 - Dev for lib & digi resource description
 - Derived from a subset of MARC 21 fields

   Dev by LC, 2002
   Specifically by Network Development & MARC Standards Office
   MODS Editorial Committee

 - Uses language-based tags
 - Does not use numeric MARC tags  



`// BIBFRAME \\`
  
  Dev by LC, 2012
  Dev partner Zepheira
  
  Linked Data bibliographic data model designed to `replace MARC`.

  Uses RDF & Linked Data principles
  Based on Linked Data Prinicples

  `WII ASE`

 > Core BIBFRAME Model:
   1. Work: Intellectual or artistic creation eg: Hamlet
   2. Instance: Specific edition/verson of a work
   3. Item: Individual copy owned by a library

 > Additional Classes:
   1. Agent: Person/org responsible
   2. Subject: Topic of resources
   3. Event: Associated event



`\\ Thesaurus //`

  Controlled Vocab that lists standarized terms(descriptors)

 > Types of Term Relationships
   1. Equivalence Relationship
      > USE/UF (Used For)
        USE : Preferred term
        UF  : Non-preferred Term
      Eg: Automobile USE: Car
          Car UF: Automobile
 
   2. Hierarchial Relationship
      > BT/NT
        BT (Broader Term)  - Wider COncept
        NT (Narrower term) - Specific Concept
      Eg: Animal (BT)
           Dog (NT)
 
   3. Associative Relationship
      > RT (Related Term)
        Terms that are related but not hierarchial
        Eg: Library RT Information Science
  
 > Components
    Descriptors (Preferred terms)
    Non-descriptors (synonyms)
    Cross references
    Scope notes (definition of terms)
    Hierarchial structure

 > Types of Thesauri
   1. Monolingual Thesaurus
       Single Language
   2. Multilingual Thesaurus
       Multiple Languages supported
   3. Specialised Thesaurus
       Subject-speific

 > Examples of Thesauri
    LCSH, ERIC, MeSH

     




`// Subject Indexing Language \\`
  controlled language used to represent the subject content of documents for indexing and retrieval.

 > Types of SIL
  1. Natural Language
      Uses everyday words
      No control or standardization

  2. Controlled Vocabulary
      Standardized terms are used
      eg: LCSH

  3. Classification Schemes
      Concepts arranged in hierarchial order
      eg: Dewy Decimal Classification
  
  4. Thesauri
      Controlled vocabulary with semantic relationships
      BT,NT,RT relation
      
 
 > Principles of SIL
  1. Principle of Specificity
      Index using the most specific term possible
       eg: 'Dog' instead of 'Animal'

  2. Principle of Exhaustivity
      Number of concepts covered in indexing
      High exhaustivity → More terms assigned
      Low exhaustivity → Fewer terms assigned
  
  3. Principle of Consistency
      Same doc → Same indexing terms
  
  4. Principle of User Orientation
      Indexing should match user search behavior

  5. Principle of Economy
      Balance between effort & retrieval effectiveness





`// (SIL) of G. Bhattacharyya \\`
    Developed POPSI based Rangas facet analysis & postulates

  `Types of SIL`
  > Verbal Subject Indexing Languages
    Subject headings
    Thesauri
    POPSI
    PRECIS

  > Notational Subject Indexing Languages
    Classification numbers
    DDC
    CC
    UDC


`// Major Lists of Subject Headings \\`

 > Library of Congress Subject Headings (LCSH)
   Dev by LC,  1898
   Pre-coordinate system
   Alphabetical arrangement

   - Structure
      Main Headings
      Subdivisions
       Topical, Geo, Chrono, Form

   - References Used:
      USE, UF, BT,NT, RT



 > Sears List of Subject Headings
   Dev by Minnie Earl Sears, 1923

   Designed for small and medium libraries
   Simpler than LCSH
   Alphabetical arrangement

   - Structure
      Main Headings
      Subdivisions
      Cross References
       USE
       UF
       BT, NT, RT

 > Medical Subject Headings (MeSH)
    By National Library of Medicine (NLM), USA, 1960
    
    Medical Subject Headings (MeSH)
    For biomedical and health-related information.

    Used in:
     MEDLINE
     PubMed
     NLM Catlogues & DB








`///// Pre-coordinate Indexing \\\\\`
  Term coordination done before storage/index preparation
  Indexer decides the order & relationship of terms

  > Major Systems
     Chain Indexing 	SR Ranganathan
     POPSI          	Ganesh Bhattacharyya
     PRECIS         	Derek Austin
     Library of Congress Subject Headings (LCSH) (line 837)

  - Compound subject represented as a heading/string.



`// Chain Indexing \\`

  Deriving subject headings from class numbers assigned during Classifcation

  Creates an alphabetical subject index by tracing the chain of broader classes from a specific subject.

  Dev by SR Ranganathan, 1938

  Specific → Broader → Broadest.
  Pre-coordinate indexing
  Uses chain of classes

  Based on `Principle of Context` principle
  Output: `Alphabetical subject index`

  Eg: Subject: Photosynthesis
  Eg: Chain: 
      Photosynthesis
      Plant Physiology
      Botany
      Biology
      Science

  > Missing Link:
     A required intermediate term absent from the classification schedule.




`// PRECIS \\`
  Preserved Context Indexing System
  Dev by `Derek Austin, 1971`
  Dev for The Bristish National Bibliography (BNB)

  - Main Principle: Preservation of Context

  Pre-cordinate indexing
  Machine-genrated entries

  Based on Role operators & syntax

 > Components:
   1. Subject Statement:
       Natural language desc of subject
   2. Role Operators:
       Synbols indicating the function of each term
   3. Syntax Rules:
       Rules governing term arrangement
   4. Generated Entries:
       Multiple alphabetical entries     



`// POPSI \\`
  Analyse the subs into concepts & generate index entries

  Dev by G Bhattacharya, 1980 at DRTC
  Based on SRR General Theory of Classification

  Pre-cordinate Indexing system
  Facet-based approach
  Uses Role indicators
  Uses Classaurus (Classified thesaurus)

 > Components:
   1. Basic Subject: Main Discipline
   2. Isolate Concepts: Facets/subordinate concepts
   3. Role Indicators: Symbols indicate role of each concept 

 > Elementary Categories (DEAPM)
    Discipline
    Entity
    Action
    Property
    Modifier









`///// Post-coordinate Indexing \\\\\`
  Subject terms are assigned seperately & are coordinated by the user
  `At the time of serach`

  - Uses single terms (Descriptors/uniterms)

  > Major Systems
      Uniterm Indexing              Mortimer Taube
      Batten System                 William Ernest Batten
      Peek-a-boo System	
      Optical Coincidence System	


`// Uniterm Indexing \\`
  Dev by Mortimer Taube, 1953

  Uses single terms (Uniterms) for indexing
  Simplest form of post-coordinate indexing

  Higly Flexible
  Better for interdisciplinary subjects
  Suitable for computer-based retrieval




`// Automatic Indexing \\`
  Generating index terms automatically by a computer
  terms extracted from, titles,  abstracts, full text etc

 > Techniques
   1. Keyword Indexing:
       Extracts significant words from doc
   2. KWIC (Key Word In COntext):
       Keyword displayed with surrounding context
   3. KWOC (Key Word Out of COntext):
       Keyword seperated from its original context
   4. Statistical Indexing:
       Uses term frequency & occurrence patterns
   5. Natural Language Processing (NLP):
       Uses linguistic analysis to identify concepts

    > NLP Tools
      NLTK              Teaching & research NLP
      spaCy             Fast NLP processing
      Stanford CoreNLP	Advanced language analysis
      Lucene	          Search & retrieval
      Elasticsearch	    Digital library search
      WordNet	          Vocabulary control & semantics
      Gensim	          Topic modeling